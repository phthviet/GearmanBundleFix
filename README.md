GearmanBundleFix
================

Fix some hot issue from mmoreramerino/GearmanBundle

Install:
--------
Symfony 2.0.x

`deps`

    [GearmanBundleFix]
    git=git://github.com/phthviet/GearmanBundleFix.git
    target=/bundles/Phthviet/GearmanBundleFix

`autoload.php`

    'Phthviet'         => __DIR__ . '/../vendor/bundles/Phthviet/GearmanBundleFix/src'

Symfony 2.1.x

    "require": {
        "phthviet/gearman-bundle-fix":"*"
    }


Configuration:
--------------

`GearmanWorkers` is the defaut directory of worker location. If you want to change it, set `gearman.worker_dir` in parameter.