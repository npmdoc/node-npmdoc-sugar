# api documentation for  [sugar (v2.0.4)](https://sugarjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-sugar.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sugar) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sugar.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sugar)
#### A Javascript utility library for working with native objects.

[![NPM](https://nodei.co/npm/sugar.png?downloads=true)](https://www.npmjs.com/package/sugar)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sugar/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sugar_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sugar/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sugar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sugar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Plummer",
        "email": "plummer.andrew@gmail.com"
    },
    "browser": {
        "buffer": false
    },
    "bugs": {
        "url": "https://github.com/andrewplummer/Sugar/issues"
    },
    "dependencies": {
        "sugar-core": "^2.0.0"
    },
    "description": "A Javascript utility library for working with native objects.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "79a6fa4dabc587fb855a52ee7176dd042bf757b0",
        "tarball": "https://registry.npmjs.org/sugar/-/sugar-2.0.4.tgz"
    },
    "engines": {
        "node": ">= 0.8.23"
    },
    "gitHead": "023fc66e77c7a08cb9ac73c01f51f44d6eee296e",
    "homepage": "https://sugarjs.com/",
    "icon": "https://sugarjs.com/icon.svg",
    "keywords": [
        "sugar",
        "sugarjs",
        "functional",
        "browser",
        "utility",
        "util",
        "date",
        "time",
        "polyfill"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "l_andrew_l",
            "email": "plummer.andrew@gmail.com"
        }
    ],
    "name": "sugar",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andrewplummer/Sugar.git"
    },
    "scripts": {},
    "typings": "sugar.d.ts",
    "version": "2.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sugar](#apidoc.module.sugar)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array {{signature}}](#apidoc.element.sugar.Array)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.count (a)](#apidoc.element.sugar.Array.count)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.every (a)](#apidoc.element.sugar.Array.every)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.filter (a)](#apidoc.element.sugar.Array.filter)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.find (a)](#apidoc.element.sugar.Array.find)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.findIndex (a)](#apidoc.element.sugar.Array.findIndex)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.map (a)](#apidoc.element.sugar.Array.map)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.none (a)](#apidoc.element.sugar.Array.none)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array.some (a)](#apidoc.element.sugar.Array.some)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Date {{signature}}](#apidoc.element.sugar.Date)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Function {{signature}}](#apidoc.element.sugar.Function)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Number {{signature}}](#apidoc.element.sugar.Number)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Object {{signature}}](#apidoc.element.sugar.Object)
1.  [function <span class="apidocSignatureSpan">sugar.</span>RegExp {{signature}}](#apidoc.element.sugar.RegExp)
1.  [function <span class="apidocSignatureSpan">sugar.</span>String {{signature}}](#apidoc.element.sugar.String)
1.  [function <span class="apidocSignatureSpan">sugar.</span>String.includes (a)](#apidoc.element.sugar.String.includes)
1.  object <span class="apidocSignatureSpan">sugar.</span>Array.prototype
1.  object <span class="apidocSignatureSpan">sugar.</span>Date.prototype
1.  object <span class="apidocSignatureSpan">sugar.</span>Function.prototype
1.  object <span class="apidocSignatureSpan">sugar.</span>Number.prototype
1.  object <span class="apidocSignatureSpan">sugar.</span>Object.prototype
1.  object <span class="apidocSignatureSpan">sugar.</span>RegExp.prototype
1.  object <span class="apidocSignatureSpan">sugar.</span>String.prototype

#### [module sugar.Array](#apidoc.module.sugar.Array)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Array {{signature}}](#apidoc.element.sugar.Array.Array)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>add (arr, item, index)](#apidoc.element.sugar.Array.add)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>append (arr, item, index)](#apidoc.element.sugar.Array.append)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>at (arr, index, loop)](#apidoc.element.sugar.Array.at)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>average (arr, map)](#apidoc.element.sugar.Array.average)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>clone (arr)](#apidoc.element.sugar.Array.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>compact (arr, all)](#apidoc.element.sugar.Array.compact)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>construct (n, fn)](#apidoc.element.sugar.Array.construct)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>count (a)](#apidoc.element.sugar.Array.count)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>create (obj, clone)](#apidoc.element.sugar.Array.create)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>every (a)](#apidoc.element.sugar.Array.every)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>everyFromIndex ()](#apidoc.element.sugar.Array.everyFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>exclude (arr, f)](#apidoc.element.sugar.Array.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>filter (a)](#apidoc.element.sugar.Array.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>filterFromIndex ()](#apidoc.element.sugar.Array.filterFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>find (a)](#apidoc.element.sugar.Array.find)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>findFromIndex ()](#apidoc.element.sugar.Array.findFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>findIndex (a)](#apidoc.element.sugar.Array.findIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>findIndexFromIndex ()](#apidoc.element.sugar.Array.findIndexFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>first (arr, num)](#apidoc.element.sugar.Array.first)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>flatten (arr, limit)](#apidoc.element.sugar.Array.flatten)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>forEachFromIndex ()](#apidoc.element.sugar.Array.forEachFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>from (arr, num)](#apidoc.element.sugar.Array.from)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>groupBy (arr, map, fn)](#apidoc.element.sugar.Array.groupBy)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>inGroups (arr, num, padding)](#apidoc.element.sugar.Array.inGroups)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>inGroupsOf (arr, num, padding)](#apidoc.element.sugar.Array.inGroupsOf)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>insert (arr, item, index)](#apidoc.element.sugar.Array.insert)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>intersect (arr1, arr2)](#apidoc.element.sugar.Array.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>isEmpty (arr)](#apidoc.element.sugar.Array.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>isEqual (a, b)](#apidoc.element.sugar.Array.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>last (arr, num)](#apidoc.element.sugar.Array.last)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>least (arr, all, map)](#apidoc.element.sugar.Array.least)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>map (a)](#apidoc.element.sugar.Array.map)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>mapFromIndex ()](#apidoc.element.sugar.Array.mapFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>max (arr, all, map)](#apidoc.element.sugar.Array.max)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>median (arr, map)](#apidoc.element.sugar.Array.median)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>min (arr, all, map)](#apidoc.element.sugar.Array.min)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>most (arr, all, map)](#apidoc.element.sugar.Array.most)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>none (a)](#apidoc.element.sugar.Array.none)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>reduceFromIndex ()](#apidoc.element.sugar.Array.reduceFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>reduceRightFromIndex ()](#apidoc.element.sugar.Array.reduceRightFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>remove (arr, f)](#apidoc.element.sugar.Array.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>removeAt (arr, start, end)](#apidoc.element.sugar.Array.removeAt)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>sample (arr, arg1, arg2)](#apidoc.element.sugar.Array.sample)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>shuffle (arr)](#apidoc.element.sugar.Array.shuffle)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>some (a)](#apidoc.element.sugar.Array.some)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>someFromIndex ()](#apidoc.element.sugar.Array.someFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>sortBy (arr, map, desc)](#apidoc.element.sugar.Array.sortBy)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>subtract (arr, item)](#apidoc.element.sugar.Array.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>sum (arr, map)](#apidoc.element.sugar.Array.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>to (arr, num)](#apidoc.element.sugar.Array.to)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>union (arr1, arr2)](#apidoc.element.sugar.Array.union)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>unique (arr, map)](#apidoc.element.sugar.Array.unique)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>zip ()](#apidoc.element.sugar.Array.zip)

#### [module sugar.Array.count](#apidoc.module.sugar.Array.count)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>count (a)](#apidoc.element.sugar.Array.count.count)
1.  [function <span class="apidocSignatureSpan">sugar.Array.count.</span>instance (b)](#apidoc.element.sugar.Array.count.instance)

#### [module sugar.Array.every](#apidoc.module.sugar.Array.every)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>every (a)](#apidoc.element.sugar.Array.every.every)
1.  [function <span class="apidocSignatureSpan">sugar.Array.every.</span>instance (b)](#apidoc.element.sugar.Array.every.instance)
1.  object <span class="apidocSignatureSpan">sugar.Array.every.</span>flags

#### [module sugar.Array.filter](#apidoc.module.sugar.Array.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>filter (a)](#apidoc.element.sugar.Array.filter.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Array.filter.</span>instance (b)](#apidoc.element.sugar.Array.filter.instance)
1.  object <span class="apidocSignatureSpan">sugar.Array.filter.</span>flags

#### [module sugar.Array.find](#apidoc.module.sugar.Array.find)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>find (a)](#apidoc.element.sugar.Array.find.find)
1.  [function <span class="apidocSignatureSpan">sugar.Array.find.</span>instance (b)](#apidoc.element.sugar.Array.find.instance)
1.  object <span class="apidocSignatureSpan">sugar.Array.find.</span>flags

#### [module sugar.Array.findIndex](#apidoc.module.sugar.Array.findIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>findIndex (a)](#apidoc.element.sugar.Array.findIndex.findIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.findIndex.</span>instance (b)](#apidoc.element.sugar.Array.findIndex.instance)
1.  object <span class="apidocSignatureSpan">sugar.Array.findIndex.</span>flags

#### [module sugar.Array.map](#apidoc.module.sugar.Array.map)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>map (a)](#apidoc.element.sugar.Array.map.map)
1.  [function <span class="apidocSignatureSpan">sugar.Array.map.</span>instance (b)](#apidoc.element.sugar.Array.map.instance)
1.  object <span class="apidocSignatureSpan">sugar.Array.map.</span>flags

#### [module sugar.Array.none](#apidoc.module.sugar.Array.none)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>none (a)](#apidoc.element.sugar.Array.none.none)
1.  [function <span class="apidocSignatureSpan">sugar.Array.none.</span>instance (b)](#apidoc.element.sugar.Array.none.instance)

#### [module sugar.Array.prototype](#apidoc.module.sugar.Array.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Array.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Array.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Array.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Array.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>add ()](#apidoc.element.sugar.Array.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>addAll ()](#apidoc.element.sugar.Array.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>append ()](#apidoc.element.sugar.Array.prototype.append)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>at ()](#apidoc.element.sugar.Array.prototype.at)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>average ()](#apidoc.element.sugar.Array.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>clone ()](#apidoc.element.sugar.Array.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>compact ()](#apidoc.element.sugar.Array.prototype.compact)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>concat ()](#apidoc.element.sugar.Array.prototype.concat)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>copyWithin ()](#apidoc.element.sugar.Array.prototype.copyWithin)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>count ()](#apidoc.element.sugar.Array.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>defaults ()](#apidoc.element.sugar.Array.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>entries ()](#apidoc.element.sugar.Array.prototype.entries)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>every ()](#apidoc.element.sugar.Array.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>everyFromIndex ()](#apidoc.element.sugar.Array.prototype.everyFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>exclude ()](#apidoc.element.sugar.Array.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>fill ()](#apidoc.element.sugar.Array.prototype.fill)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>filter ()](#apidoc.element.sugar.Array.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>filterFromIndex ()](#apidoc.element.sugar.Array.prototype.filterFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>find ()](#apidoc.element.sugar.Array.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>findFromIndex ()](#apidoc.element.sugar.Array.prototype.findFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>findIndex ()](#apidoc.element.sugar.Array.prototype.findIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>findIndexFromIndex ()](#apidoc.element.sugar.Array.prototype.findIndexFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>first ()](#apidoc.element.sugar.Array.prototype.first)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>flatten ()](#apidoc.element.sugar.Array.prototype.flatten)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>forEach ()](#apidoc.element.sugar.Array.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>forEachFromIndex ()](#apidoc.element.sugar.Array.prototype.forEachFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>from ()](#apidoc.element.sugar.Array.prototype.from)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>get ()](#apidoc.element.sugar.Array.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>groupBy ()](#apidoc.element.sugar.Array.prototype.groupBy)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>has ()](#apidoc.element.sugar.Array.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Array.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>inGroups ()](#apidoc.element.sugar.Array.prototype.inGroups)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>inGroupsOf ()](#apidoc.element.sugar.Array.prototype.inGroupsOf)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>includes ()](#apidoc.element.sugar.Array.prototype.includes)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>indexOf ()](#apidoc.element.sugar.Array.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>insert ()](#apidoc.element.sugar.Array.prototype.insert)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>intersect ()](#apidoc.element.sugar.Array.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>invert ()](#apidoc.element.sugar.Array.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isArguments ()](#apidoc.element.sugar.Array.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isArray ()](#apidoc.element.sugar.Array.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isBoolean ()](#apidoc.element.sugar.Array.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isDate ()](#apidoc.element.sugar.Array.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isEmpty ()](#apidoc.element.sugar.Array.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isEqual ()](#apidoc.element.sugar.Array.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isError ()](#apidoc.element.sugar.Array.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isFunction ()](#apidoc.element.sugar.Array.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isMap ()](#apidoc.element.sugar.Array.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isNumber ()](#apidoc.element.sugar.Array.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isObject ()](#apidoc.element.sugar.Array.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Array.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isRegExp ()](#apidoc.element.sugar.Array.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isSet ()](#apidoc.element.sugar.Array.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isString ()](#apidoc.element.sugar.Array.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>join ()](#apidoc.element.sugar.Array.prototype.join)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>keys ()](#apidoc.element.sugar.Array.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>last ()](#apidoc.element.sugar.Array.prototype.last)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>lastIndexOf ()](#apidoc.element.sugar.Array.prototype.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>least ()](#apidoc.element.sugar.Array.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>map ()](#apidoc.element.sugar.Array.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>mapFromIndex ()](#apidoc.element.sugar.Array.prototype.mapFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>max ()](#apidoc.element.sugar.Array.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>median ()](#apidoc.element.sugar.Array.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>merge ()](#apidoc.element.sugar.Array.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>mergeAll ()](#apidoc.element.sugar.Array.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>min ()](#apidoc.element.sugar.Array.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>most ()](#apidoc.element.sugar.Array.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>none ()](#apidoc.element.sugar.Array.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>pop ()](#apidoc.element.sugar.Array.prototype.pop)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Array.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>push ()](#apidoc.element.sugar.Array.prototype.push)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduce ()](#apidoc.element.sugar.Array.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduceFromIndex ()](#apidoc.element.sugar.Array.prototype.reduceFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduceRight ()](#apidoc.element.sugar.Array.prototype.reduceRight)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduceRightFromIndex ()](#apidoc.element.sugar.Array.prototype.reduceRightFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reject ()](#apidoc.element.sugar.Array.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>remove ()](#apidoc.element.sugar.Array.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>removeAt ()](#apidoc.element.sugar.Array.prototype.removeAt)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reverse ()](#apidoc.element.sugar.Array.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sample ()](#apidoc.element.sugar.Array.prototype.sample)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>select ()](#apidoc.element.sugar.Array.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>set ()](#apidoc.element.sugar.Array.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>shift ()](#apidoc.element.sugar.Array.prototype.shift)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>shuffle ()](#apidoc.element.sugar.Array.prototype.shuffle)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>size ()](#apidoc.element.sugar.Array.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>slice ()](#apidoc.element.sugar.Array.prototype.slice)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>some ()](#apidoc.element.sugar.Array.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>someFromIndex ()](#apidoc.element.sugar.Array.prototype.someFromIndex)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sort ()](#apidoc.element.sugar.Array.prototype.sort)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sortBy ()](#apidoc.element.sugar.Array.prototype.sortBy)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>splice ()](#apidoc.element.sugar.Array.prototype.splice)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>subtract ()](#apidoc.element.sugar.Array.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sum ()](#apidoc.element.sugar.Array.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>tap ()](#apidoc.element.sugar.Array.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>to ()](#apidoc.element.sugar.Array.prototype.to)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Array.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>toQueryString ()](#apidoc.element.sugar.Array.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>toString ()](#apidoc.element.sugar.Array.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>union ()](#apidoc.element.sugar.Array.prototype.union)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>unique ()](#apidoc.element.sugar.Array.prototype.unique)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>unshift ()](#apidoc.element.sugar.Array.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>values ()](#apidoc.element.sugar.Array.prototype.values)
1.  [function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>zip ()](#apidoc.element.sugar.Array.prototype.zip)

#### [module sugar.Array.some](#apidoc.module.sugar.Array.some)
1.  [function <span class="apidocSignatureSpan">sugar.Array.</span>some (a)](#apidoc.element.sugar.Array.some.some)
1.  [function <span class="apidocSignatureSpan">sugar.Array.some.</span>instance (b)](#apidoc.element.sugar.Array.some.instance)
1.  object <span class="apidocSignatureSpan">sugar.Array.some.</span>flags

#### [module sugar.Date](#apidoc.module.sugar.Date)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Date {{signature}}](#apidoc.element.sugar.Date.Date)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addDays (d, num, reset)](#apidoc.element.sugar.Date.addDays)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addHours (d, num, reset)](#apidoc.element.sugar.Date.addHours)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addLocale (code, set)](#apidoc.element.sugar.Date.addLocale)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addMilliseconds (d, num, reset)](#apidoc.element.sugar.Date.addMilliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addMinutes (d, num, reset)](#apidoc.element.sugar.Date.addMinutes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addMonths (d, num, reset)](#apidoc.element.sugar.Date.addMonths)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addSeconds (d, num, reset)](#apidoc.element.sugar.Date.addSeconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addWeeks (d, num, reset)](#apidoc.element.sugar.Date.addWeeks)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>addYears (d, num, reset)](#apidoc.element.sugar.Date.addYears)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>advance ()](#apidoc.element.sugar.Date.advance)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfDay (d, localeCode)](#apidoc.element.sugar.Date.beginningOfDay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfISOWeek (date)](#apidoc.element.sugar.Date.beginningOfISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfMonth (d, localeCode)](#apidoc.element.sugar.Date.beginningOfMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfWeek (d, localeCode)](#apidoc.element.sugar.Date.beginningOfWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfYear (d, localeCode)](#apidoc.element.sugar.Date.beginningOfYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>clone (date)](#apidoc.element.sugar.Date.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>create (d, options)](#apidoc.element.sugar.Date.create)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>daysAgo (date, d, options)](#apidoc.element.sugar.Date.daysAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>daysFromNow (date, d, options)](#apidoc.element.sugar.Date.daysFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>daysInMonth (date)](#apidoc.element.sugar.Date.daysInMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>daysSince (date, d, options)](#apidoc.element.sugar.Date.daysSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>daysUntil (date, d, options)](#apidoc.element.sugar.Date.daysUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>endOfDay (d, localeCode)](#apidoc.element.sugar.Date.endOfDay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>endOfISOWeek (date)](#apidoc.element.sugar.Date.endOfISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>endOfMonth (d, localeCode)](#apidoc.element.sugar.Date.endOfMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>endOfWeek (d, localeCode)](#apidoc.element.sugar.Date.endOfWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>endOfYear (d, localeCode)](#apidoc.element.sugar.Date.endOfYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>format (date, f, localeCode)](#apidoc.element.sugar.Date.format)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>full (d, localeCode)](#apidoc.element.sugar.Date.full)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>get (date, d, options)](#apidoc.element.sugar.Date.get)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getAllLocaleCodes ()](#apidoc.element.sugar.Date.getAllLocaleCodes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getAllLocales ()](#apidoc.element.sugar.Date.getAllLocales)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getISOWeek (date)](#apidoc.element.sugar.Date.getISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getLocale (code)](#apidoc.element.sugar.Date.getLocale)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getUTCOffset (date, iso)](#apidoc.element.sugar.Date.getUTCOffset)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getUTCWeekday (date)](#apidoc.element.sugar.Date.getUTCWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>getWeekday (date)](#apidoc.element.sugar.Date.getWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>hoursAgo (date, d, options)](#apidoc.element.sugar.Date.hoursAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>hoursFromNow (date, d, options)](#apidoc.element.sugar.Date.hoursFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>hoursSince (date, d, options)](#apidoc.element.sugar.Date.hoursSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>hoursUntil (date, d, options)](#apidoc.element.sugar.Date.hoursUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>is (date, d, margin)](#apidoc.element.sugar.Date.is)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isAfter (date, d, margin)](#apidoc.element.sugar.Date.isAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isApril (d)](#apidoc.element.sugar.Date.isApril)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isAugust (d)](#apidoc.element.sugar.Date.isAugust)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isBefore (date, d, margin)](#apidoc.element.sugar.Date.isBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isBetween (date, d1, d2, margin)](#apidoc.element.sugar.Date.isBetween)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isDecember (d)](#apidoc.element.sugar.Date.isDecember)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isFebruary (d)](#apidoc.element.sugar.Date.isFebruary)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isFriday (d)](#apidoc.element.sugar.Date.isFriday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isFuture (d)](#apidoc.element.sugar.Date.isFuture)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isJanuary (d)](#apidoc.element.sugar.Date.isJanuary)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isJuly (d)](#apidoc.element.sugar.Date.isJuly)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isJune (d)](#apidoc.element.sugar.Date.isJune)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isLastMonth (d, localeCode)](#apidoc.element.sugar.Date.isLastMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isLastWeek (d, localeCode)](#apidoc.element.sugar.Date.isLastWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isLastYear (d, localeCode)](#apidoc.element.sugar.Date.isLastYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isLeapYear (date)](#apidoc.element.sugar.Date.isLeapYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isMarch (d)](#apidoc.element.sugar.Date.isMarch)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isMay (d)](#apidoc.element.sugar.Date.isMay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isMonday (d)](#apidoc.element.sugar.Date.isMonday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isNextMonth (d, localeCode)](#apidoc.element.sugar.Date.isNextMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isNextWeek (d, localeCode)](#apidoc.element.sugar.Date.isNextWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isNextYear (d, localeCode)](#apidoc.element.sugar.Date.isNextYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isNovember (d)](#apidoc.element.sugar.Date.isNovember)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isOctober (d)](#apidoc.element.sugar.Date.isOctober)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isPast (d)](#apidoc.element.sugar.Date.isPast)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isSaturday (d)](#apidoc.element.sugar.Date.isSaturday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isSeptember (d)](#apidoc.element.sugar.Date.isSeptember)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isSunday (d)](#apidoc.element.sugar.Date.isSunday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isThisMonth (d, localeCode)](#apidoc.element.sugar.Date.isThisMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isThisWeek (d, localeCode)](#apidoc.element.sugar.Date.isThisWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isThisYear (d, localeCode)](#apidoc.element.sugar.Date.isThisYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isThursday (d)](#apidoc.element.sugar.Date.isThursday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isToday (d)](#apidoc.element.sugar.Date.isToday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isTomorrow (d)](#apidoc.element.sugar.Date.isTomorrow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isTuesday (d)](#apidoc.element.sugar.Date.isTuesday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isUTC (date)](#apidoc.element.sugar.Date.isUTC)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isValid (date)](#apidoc.element.sugar.Date.isValid)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isWednesday (d)](#apidoc.element.sugar.Date.isWednesday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isWeekday (d)](#apidoc.element.sugar.Date.isWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isWeekend (d)](#apidoc.element.sugar.Date.isWeekend)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>isYesterday (d)](#apidoc.element.sugar.Date.isYesterday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>iso (date)](#apidoc.element.sugar.Date.iso)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>long (d, localeCode)](#apidoc.element.sugar.Date.long)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>medium (d, localeCode)](#apidoc.element.sugar.Date.medium)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsAgo (date, d, options)](#apidoc.element.sugar.Date.millisecondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsFromNow (date, d, options)](#apidoc.element.sugar.Date.millisecondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsSince (date, d, options)](#apidoc.element.sugar.Date.millisecondsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsUntil (date, d, options)](#apidoc.element.sugar.Date.millisecondsUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>minutesAgo (date, d, options)](#apidoc.element.sugar.Date.minutesAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>minutesFromNow (date, d, options)](#apidoc.element.sugar.Date.minutesFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>minutesSince (date, d, options)](#apidoc.element.sugar.Date.minutesSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>minutesUntil (date, d, options)](#apidoc.element.sugar.Date.minutesUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>monthsAgo (date, d, options)](#apidoc.element.sugar.Date.monthsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>monthsFromNow (date, d, options)](#apidoc.element.sugar.Date.monthsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>monthsSince (date, d, options)](#apidoc.element.sugar.Date.monthsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>monthsUntil (date, d, options)](#apidoc.element.sugar.Date.monthsUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>range (start, end)](#apidoc.element.sugar.Date.range)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>relative (date, localeCode, fn)](#apidoc.element.sugar.Date.relative)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>relativeTo (date, d, localeCode)](#apidoc.element.sugar.Date.relativeTo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>removeLocale (code)](#apidoc.element.sugar.Date.removeLocale)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>reset (date, unit, localeCode)](#apidoc.element.sugar.Date.reset)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>rewind ()](#apidoc.element.sugar.Date.rewind)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>secondsAgo (date, d, options)](#apidoc.element.sugar.Date.secondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>secondsFromNow (date, d, options)](#apidoc.element.sugar.Date.secondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>secondsSince (date, d, options)](#apidoc.element.sugar.Date.secondsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>secondsUntil (date, d, options)](#apidoc.element.sugar.Date.secondsUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>set ()](#apidoc.element.sugar.Date.set)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>setISOWeek (date, num)](#apidoc.element.sugar.Date.setISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>setLocale (code)](#apidoc.element.sugar.Date.setLocale)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>setUTC (date, on)](#apidoc.element.sugar.Date.setUTC)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>setWeekday (date, dow)](#apidoc.element.sugar.Date.setWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>short (d, localeCode)](#apidoc.element.sugar.Date.short)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>weeksAgo (date, d, options)](#apidoc.element.sugar.Date.weeksAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>weeksFromNow (date, d, options)](#apidoc.element.sugar.Date.weeksFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>weeksSince (date, d, options)](#apidoc.element.sugar.Date.weeksSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>weeksUntil (date, d, options)](#apidoc.element.sugar.Date.weeksUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>yearsAgo (date, d, options)](#apidoc.element.sugar.Date.yearsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>yearsFromNow (date, d, options)](#apidoc.element.sugar.Date.yearsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>yearsSince (date, d, options)](#apidoc.element.sugar.Date.yearsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.</span>yearsUntil (date, d, options)](#apidoc.element.sugar.Date.yearsUntil)

#### [module sugar.Date.prototype](#apidoc.module.sugar.Date.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Date.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Date.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Date.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Date.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>add ()](#apidoc.element.sugar.Date.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addAll ()](#apidoc.element.sugar.Date.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addDays ()](#apidoc.element.sugar.Date.prototype.addDays)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addHours ()](#apidoc.element.sugar.Date.prototype.addHours)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addMilliseconds ()](#apidoc.element.sugar.Date.prototype.addMilliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addMinutes ()](#apidoc.element.sugar.Date.prototype.addMinutes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addMonths ()](#apidoc.element.sugar.Date.prototype.addMonths)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addSeconds ()](#apidoc.element.sugar.Date.prototype.addSeconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addWeeks ()](#apidoc.element.sugar.Date.prototype.addWeeks)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addYears ()](#apidoc.element.sugar.Date.prototype.addYears)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>advance ()](#apidoc.element.sugar.Date.prototype.advance)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>average ()](#apidoc.element.sugar.Date.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfDay ()](#apidoc.element.sugar.Date.prototype.beginningOfDay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfISOWeek ()](#apidoc.element.sugar.Date.prototype.beginningOfISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfMonth ()](#apidoc.element.sugar.Date.prototype.beginningOfMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfWeek ()](#apidoc.element.sugar.Date.prototype.beginningOfWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfYear ()](#apidoc.element.sugar.Date.prototype.beginningOfYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>clone ()](#apidoc.element.sugar.Date.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>count ()](#apidoc.element.sugar.Date.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysAgo ()](#apidoc.element.sugar.Date.prototype.daysAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysFromNow ()](#apidoc.element.sugar.Date.prototype.daysFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysInMonth ()](#apidoc.element.sugar.Date.prototype.daysInMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysSince ()](#apidoc.element.sugar.Date.prototype.daysSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysUntil ()](#apidoc.element.sugar.Date.prototype.daysUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>defaults ()](#apidoc.element.sugar.Date.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfDay ()](#apidoc.element.sugar.Date.prototype.endOfDay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfISOWeek ()](#apidoc.element.sugar.Date.prototype.endOfISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfMonth ()](#apidoc.element.sugar.Date.prototype.endOfMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfWeek ()](#apidoc.element.sugar.Date.prototype.endOfWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfYear ()](#apidoc.element.sugar.Date.prototype.endOfYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>every ()](#apidoc.element.sugar.Date.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>exclude ()](#apidoc.element.sugar.Date.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>filter ()](#apidoc.element.sugar.Date.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>find ()](#apidoc.element.sugar.Date.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>forEach ()](#apidoc.element.sugar.Date.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>format ()](#apidoc.element.sugar.Date.prototype.format)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>full ()](#apidoc.element.sugar.Date.prototype.full)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>get ()](#apidoc.element.sugar.Date.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getDate ()](#apidoc.element.sugar.Date.prototype.getDate)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getDay ()](#apidoc.element.sugar.Date.prototype.getDay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getFullYear ()](#apidoc.element.sugar.Date.prototype.getFullYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getHours ()](#apidoc.element.sugar.Date.prototype.getHours)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getISOWeek ()](#apidoc.element.sugar.Date.prototype.getISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getMilliseconds ()](#apidoc.element.sugar.Date.prototype.getMilliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getMinutes ()](#apidoc.element.sugar.Date.prototype.getMinutes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getMonth ()](#apidoc.element.sugar.Date.prototype.getMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getSeconds ()](#apidoc.element.sugar.Date.prototype.getSeconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getTime ()](#apidoc.element.sugar.Date.prototype.getTime)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getTimezoneOffset ()](#apidoc.element.sugar.Date.prototype.getTimezoneOffset)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCDate ()](#apidoc.element.sugar.Date.prototype.getUTCDate)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCDay ()](#apidoc.element.sugar.Date.prototype.getUTCDay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCFullYear ()](#apidoc.element.sugar.Date.prototype.getUTCFullYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCHours ()](#apidoc.element.sugar.Date.prototype.getUTCHours)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCMilliseconds ()](#apidoc.element.sugar.Date.prototype.getUTCMilliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCMinutes ()](#apidoc.element.sugar.Date.prototype.getUTCMinutes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCMonth ()](#apidoc.element.sugar.Date.prototype.getUTCMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCOffset ()](#apidoc.element.sugar.Date.prototype.getUTCOffset)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCSeconds ()](#apidoc.element.sugar.Date.prototype.getUTCSeconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCWeekday ()](#apidoc.element.sugar.Date.prototype.getUTCWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getWeekday ()](#apidoc.element.sugar.Date.prototype.getWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getYear ()](#apidoc.element.sugar.Date.prototype.getYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>has ()](#apidoc.element.sugar.Date.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Date.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursAgo ()](#apidoc.element.sugar.Date.prototype.hoursAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursFromNow ()](#apidoc.element.sugar.Date.prototype.hoursFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursSince ()](#apidoc.element.sugar.Date.prototype.hoursSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursUntil ()](#apidoc.element.sugar.Date.prototype.hoursUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>intersect ()](#apidoc.element.sugar.Date.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>invert ()](#apidoc.element.sugar.Date.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>is ()](#apidoc.element.sugar.Date.prototype.is)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isAfter ()](#apidoc.element.sugar.Date.prototype.isAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isApril ()](#apidoc.element.sugar.Date.prototype.isApril)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isArguments ()](#apidoc.element.sugar.Date.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isArray ()](#apidoc.element.sugar.Date.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isAugust ()](#apidoc.element.sugar.Date.prototype.isAugust)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isBefore ()](#apidoc.element.sugar.Date.prototype.isBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isBetween ()](#apidoc.element.sugar.Date.prototype.isBetween)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isBoolean ()](#apidoc.element.sugar.Date.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isDate ()](#apidoc.element.sugar.Date.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isDecember ()](#apidoc.element.sugar.Date.prototype.isDecember)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isEmpty ()](#apidoc.element.sugar.Date.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isEqual ()](#apidoc.element.sugar.Date.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isError ()](#apidoc.element.sugar.Date.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFebruary ()](#apidoc.element.sugar.Date.prototype.isFebruary)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFriday ()](#apidoc.element.sugar.Date.prototype.isFriday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFunction ()](#apidoc.element.sugar.Date.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFuture ()](#apidoc.element.sugar.Date.prototype.isFuture)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isJanuary ()](#apidoc.element.sugar.Date.prototype.isJanuary)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isJuly ()](#apidoc.element.sugar.Date.prototype.isJuly)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isJune ()](#apidoc.element.sugar.Date.prototype.isJune)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLastMonth ()](#apidoc.element.sugar.Date.prototype.isLastMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLastWeek ()](#apidoc.element.sugar.Date.prototype.isLastWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLastYear ()](#apidoc.element.sugar.Date.prototype.isLastYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLeapYear ()](#apidoc.element.sugar.Date.prototype.isLeapYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMap ()](#apidoc.element.sugar.Date.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMarch ()](#apidoc.element.sugar.Date.prototype.isMarch)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMay ()](#apidoc.element.sugar.Date.prototype.isMay)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMonday ()](#apidoc.element.sugar.Date.prototype.isMonday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNextMonth ()](#apidoc.element.sugar.Date.prototype.isNextMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNextWeek ()](#apidoc.element.sugar.Date.prototype.isNextWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNextYear ()](#apidoc.element.sugar.Date.prototype.isNextYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNovember ()](#apidoc.element.sugar.Date.prototype.isNovember)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNumber ()](#apidoc.element.sugar.Date.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isObject ()](#apidoc.element.sugar.Date.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isOctober ()](#apidoc.element.sugar.Date.prototype.isOctober)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isPast ()](#apidoc.element.sugar.Date.prototype.isPast)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Date.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isRegExp ()](#apidoc.element.sugar.Date.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSaturday ()](#apidoc.element.sugar.Date.prototype.isSaturday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSeptember ()](#apidoc.element.sugar.Date.prototype.isSeptember)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSet ()](#apidoc.element.sugar.Date.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isString ()](#apidoc.element.sugar.Date.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSunday ()](#apidoc.element.sugar.Date.prototype.isSunday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThisMonth ()](#apidoc.element.sugar.Date.prototype.isThisMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThisWeek ()](#apidoc.element.sugar.Date.prototype.isThisWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThisYear ()](#apidoc.element.sugar.Date.prototype.isThisYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThursday ()](#apidoc.element.sugar.Date.prototype.isThursday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isToday ()](#apidoc.element.sugar.Date.prototype.isToday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isTomorrow ()](#apidoc.element.sugar.Date.prototype.isTomorrow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isTuesday ()](#apidoc.element.sugar.Date.prototype.isTuesday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isUTC ()](#apidoc.element.sugar.Date.prototype.isUTC)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isValid ()](#apidoc.element.sugar.Date.prototype.isValid)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isWednesday ()](#apidoc.element.sugar.Date.prototype.isWednesday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isWeekday ()](#apidoc.element.sugar.Date.prototype.isWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isWeekend ()](#apidoc.element.sugar.Date.prototype.isWeekend)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isYesterday ()](#apidoc.element.sugar.Date.prototype.isYesterday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>iso ()](#apidoc.element.sugar.Date.prototype.iso)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>keys ()](#apidoc.element.sugar.Date.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>least ()](#apidoc.element.sugar.Date.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>long ()](#apidoc.element.sugar.Date.prototype.long)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>map ()](#apidoc.element.sugar.Date.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>max ()](#apidoc.element.sugar.Date.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>median ()](#apidoc.element.sugar.Date.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>medium ()](#apidoc.element.sugar.Date.prototype.medium)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>merge ()](#apidoc.element.sugar.Date.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>mergeAll ()](#apidoc.element.sugar.Date.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsAgo ()](#apidoc.element.sugar.Date.prototype.millisecondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsFromNow ()](#apidoc.element.sugar.Date.prototype.millisecondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsSince ()](#apidoc.element.sugar.Date.prototype.millisecondsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsUntil ()](#apidoc.element.sugar.Date.prototype.millisecondsUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>min ()](#apidoc.element.sugar.Date.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesAgo ()](#apidoc.element.sugar.Date.prototype.minutesAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesFromNow ()](#apidoc.element.sugar.Date.prototype.minutesFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesSince ()](#apidoc.element.sugar.Date.prototype.minutesSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesUntil ()](#apidoc.element.sugar.Date.prototype.minutesUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsAgo ()](#apidoc.element.sugar.Date.prototype.monthsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsFromNow ()](#apidoc.element.sugar.Date.prototype.monthsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsSince ()](#apidoc.element.sugar.Date.prototype.monthsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsUntil ()](#apidoc.element.sugar.Date.prototype.monthsUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>most ()](#apidoc.element.sugar.Date.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>none ()](#apidoc.element.sugar.Date.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Date.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>reduce ()](#apidoc.element.sugar.Date.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>reject ()](#apidoc.element.sugar.Date.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>relative ()](#apidoc.element.sugar.Date.prototype.relative)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>relativeTo ()](#apidoc.element.sugar.Date.prototype.relativeTo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>remove ()](#apidoc.element.sugar.Date.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>reset ()](#apidoc.element.sugar.Date.prototype.reset)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>rewind ()](#apidoc.element.sugar.Date.prototype.rewind)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsAgo ()](#apidoc.element.sugar.Date.prototype.secondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsFromNow ()](#apidoc.element.sugar.Date.prototype.secondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsSince ()](#apidoc.element.sugar.Date.prototype.secondsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsUntil ()](#apidoc.element.sugar.Date.prototype.secondsUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>select ()](#apidoc.element.sugar.Date.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>set ()](#apidoc.element.sugar.Date.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setDate ()](#apidoc.element.sugar.Date.prototype.setDate)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setFullYear ()](#apidoc.element.sugar.Date.prototype.setFullYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setHours ()](#apidoc.element.sugar.Date.prototype.setHours)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setISOWeek ()](#apidoc.element.sugar.Date.prototype.setISOWeek)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setMilliseconds ()](#apidoc.element.sugar.Date.prototype.setMilliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setMinutes ()](#apidoc.element.sugar.Date.prototype.setMinutes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setMonth ()](#apidoc.element.sugar.Date.prototype.setMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setSeconds ()](#apidoc.element.sugar.Date.prototype.setSeconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setTime ()](#apidoc.element.sugar.Date.prototype.setTime)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTC ()](#apidoc.element.sugar.Date.prototype.setUTC)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCDate ()](#apidoc.element.sugar.Date.prototype.setUTCDate)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCFullYear ()](#apidoc.element.sugar.Date.prototype.setUTCFullYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCHours ()](#apidoc.element.sugar.Date.prototype.setUTCHours)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCMilliseconds ()](#apidoc.element.sugar.Date.prototype.setUTCMilliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCMinutes ()](#apidoc.element.sugar.Date.prototype.setUTCMinutes)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCMonth ()](#apidoc.element.sugar.Date.prototype.setUTCMonth)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCSeconds ()](#apidoc.element.sugar.Date.prototype.setUTCSeconds)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setWeekday ()](#apidoc.element.sugar.Date.prototype.setWeekday)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setYear ()](#apidoc.element.sugar.Date.prototype.setYear)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>short ()](#apidoc.element.sugar.Date.prototype.short)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>size ()](#apidoc.element.sugar.Date.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>some ()](#apidoc.element.sugar.Date.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>subtract ()](#apidoc.element.sugar.Date.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>sum ()](#apidoc.element.sugar.Date.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>tap ()](#apidoc.element.sugar.Date.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toDateString ()](#apidoc.element.sugar.Date.prototype.toDateString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toGMTString ()](#apidoc.element.sugar.Date.prototype.toGMTString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toISOString ()](#apidoc.element.sugar.Date.prototype.toISOString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toJSON ()](#apidoc.element.sugar.Date.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toLocaleDateString ()](#apidoc.element.sugar.Date.prototype.toLocaleDateString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Date.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toLocaleTimeString ()](#apidoc.element.sugar.Date.prototype.toLocaleTimeString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toQueryString ()](#apidoc.element.sugar.Date.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toString ()](#apidoc.element.sugar.Date.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toTimeString ()](#apidoc.element.sugar.Date.prototype.toTimeString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toUTCString ()](#apidoc.element.sugar.Date.prototype.toUTCString)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>values ()](#apidoc.element.sugar.Date.prototype.values)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksAgo ()](#apidoc.element.sugar.Date.prototype.weeksAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksFromNow ()](#apidoc.element.sugar.Date.prototype.weeksFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksSince ()](#apidoc.element.sugar.Date.prototype.weeksSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksUntil ()](#apidoc.element.sugar.Date.prototype.weeksUntil)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsAgo ()](#apidoc.element.sugar.Date.prototype.yearsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsFromNow ()](#apidoc.element.sugar.Date.prototype.yearsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsSince ()](#apidoc.element.sugar.Date.prototype.yearsSince)
1.  [function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsUntil ()](#apidoc.element.sugar.Date.prototype.yearsUntil)

#### [module sugar.Function](#apidoc.module.sugar.Function)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Function {{signature}}](#apidoc.element.sugar.Function.Function)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>after (fn, num)](#apidoc.element.sugar.Function.after)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>cancel (fn)](#apidoc.element.sugar.Function.cancel)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>debounce (fn, ms)](#apidoc.element.sugar.Function.debounce)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>delay ()](#apidoc.element.sugar.Function.delay)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>every ()](#apidoc.element.sugar.Function.every)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>lazy (fn, ms, immediate, limit)](#apidoc.element.sugar.Function.lazy)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>lock (fn, n)](#apidoc.element.sugar.Function.lock)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>memoize (fn, arg1, arg2)](#apidoc.element.sugar.Function.memoize)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>once (fn)](#apidoc.element.sugar.Function.once)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>partial ()](#apidoc.element.sugar.Function.partial)
1.  [function <span class="apidocSignatureSpan">sugar.Function.</span>throttle (fn, ms)](#apidoc.element.sugar.Function.throttle)

#### [module sugar.Function.prototype](#apidoc.module.sugar.Function.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Function.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Function.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Function.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Function.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>add ()](#apidoc.element.sugar.Function.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>addAll ()](#apidoc.element.sugar.Function.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>after ()](#apidoc.element.sugar.Function.prototype.after)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>apply ()](#apidoc.element.sugar.Function.prototype.apply)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>average ()](#apidoc.element.sugar.Function.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>bind ()](#apidoc.element.sugar.Function.prototype.bind)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>call ()](#apidoc.element.sugar.Function.prototype.call)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>cancel ()](#apidoc.element.sugar.Function.prototype.cancel)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>clone ()](#apidoc.element.sugar.Function.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>count ()](#apidoc.element.sugar.Function.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>debounce ()](#apidoc.element.sugar.Function.prototype.debounce)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>defaults ()](#apidoc.element.sugar.Function.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>delay ()](#apidoc.element.sugar.Function.prototype.delay)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>every ()](#apidoc.element.sugar.Function.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>exclude ()](#apidoc.element.sugar.Function.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>filter ()](#apidoc.element.sugar.Function.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>find ()](#apidoc.element.sugar.Function.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>forEach ()](#apidoc.element.sugar.Function.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>get ()](#apidoc.element.sugar.Function.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>has ()](#apidoc.element.sugar.Function.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Function.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>intersect ()](#apidoc.element.sugar.Function.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>invert ()](#apidoc.element.sugar.Function.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isArguments ()](#apidoc.element.sugar.Function.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isArray ()](#apidoc.element.sugar.Function.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isBoolean ()](#apidoc.element.sugar.Function.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isDate ()](#apidoc.element.sugar.Function.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isEmpty ()](#apidoc.element.sugar.Function.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isEqual ()](#apidoc.element.sugar.Function.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isError ()](#apidoc.element.sugar.Function.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isFunction ()](#apidoc.element.sugar.Function.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isMap ()](#apidoc.element.sugar.Function.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isNumber ()](#apidoc.element.sugar.Function.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isObject ()](#apidoc.element.sugar.Function.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Function.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isRegExp ()](#apidoc.element.sugar.Function.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isSet ()](#apidoc.element.sugar.Function.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isString ()](#apidoc.element.sugar.Function.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>keys ()](#apidoc.element.sugar.Function.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>lazy ()](#apidoc.element.sugar.Function.prototype.lazy)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>least ()](#apidoc.element.sugar.Function.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>lock ()](#apidoc.element.sugar.Function.prototype.lock)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>map ()](#apidoc.element.sugar.Function.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>max ()](#apidoc.element.sugar.Function.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>median ()](#apidoc.element.sugar.Function.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>memoize ()](#apidoc.element.sugar.Function.prototype.memoize)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>merge ()](#apidoc.element.sugar.Function.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>mergeAll ()](#apidoc.element.sugar.Function.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>min ()](#apidoc.element.sugar.Function.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>most ()](#apidoc.element.sugar.Function.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>none ()](#apidoc.element.sugar.Function.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>once ()](#apidoc.element.sugar.Function.prototype.once)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>partial ()](#apidoc.element.sugar.Function.prototype.partial)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Function.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>reduce ()](#apidoc.element.sugar.Function.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>reject ()](#apidoc.element.sugar.Function.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>remove ()](#apidoc.element.sugar.Function.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>select ()](#apidoc.element.sugar.Function.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>set ()](#apidoc.element.sugar.Function.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>size ()](#apidoc.element.sugar.Function.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>some ()](#apidoc.element.sugar.Function.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>subtract ()](#apidoc.element.sugar.Function.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>sum ()](#apidoc.element.sugar.Function.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>tap ()](#apidoc.element.sugar.Function.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>throttle ()](#apidoc.element.sugar.Function.prototype.throttle)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Function.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>toQueryString ()](#apidoc.element.sugar.Function.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>toString ()](#apidoc.element.sugar.Function.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>values ()](#apidoc.element.sugar.Function.prototype.values)

#### [module sugar.Number](#apidoc.module.sugar.Number)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Number {{signature}}](#apidoc.element.sugar.Number.Number)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>abbr (n, precision)](#apidoc.element.sugar.Number.abbr)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>abs (n, arg)](#apidoc.element.sugar.Number.abs)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>acos (n, arg)](#apidoc.element.sugar.Number.acos)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>asin (n, arg)](#apidoc.element.sugar.Number.asin)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>atan (n, arg)](#apidoc.element.sugar.Number.atan)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>bytes (n, precision, binary, units)](#apidoc.element.sugar.Number.bytes)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>cap (n, max)](#apidoc.element.sugar.Number.cap)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>ceil (n, precision)](#apidoc.element.sugar.Number.ceil)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>chr (n)](#apidoc.element.sugar.Number.chr)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>clamp (n, start, end)](#apidoc.element.sugar.Number.clamp)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>cos (n, arg)](#apidoc.element.sugar.Number.cos)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>day (n)](#apidoc.element.sugar.Number.day)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>dayAfter (n, d, options)](#apidoc.element.sugar.Number.dayAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>dayAgo (n, d, options)](#apidoc.element.sugar.Number.dayAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>dayBefore (n, d, options)](#apidoc.element.sugar.Number.dayBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>dayFromNow (n, d, options)](#apidoc.element.sugar.Number.dayFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>days (n)](#apidoc.element.sugar.Number.days)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>daysAfter (n, d, options)](#apidoc.element.sugar.Number.daysAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>daysAgo (n, d, options)](#apidoc.element.sugar.Number.daysAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>daysBefore (n, d, options)](#apidoc.element.sugar.Number.daysBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>daysFromNow (n, d, options)](#apidoc.element.sugar.Number.daysFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>downto (n, num, step, fn)](#apidoc.element.sugar.Number.downto)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>duration (n, localeCode)](#apidoc.element.sugar.Number.duration)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>exp (n, arg)](#apidoc.element.sugar.Number.exp)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>floor (n, precision)](#apidoc.element.sugar.Number.floor)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>format (n, place)](#apidoc.element.sugar.Number.format)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hex (n, pad)](#apidoc.element.sugar.Number.hex)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hour (n)](#apidoc.element.sugar.Number.hour)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hourAfter (n, d, options)](#apidoc.element.sugar.Number.hourAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hourAgo (n, d, options)](#apidoc.element.sugar.Number.hourAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hourBefore (n, d, options)](#apidoc.element.sugar.Number.hourBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hourFromNow (n, d, options)](#apidoc.element.sugar.Number.hourFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hours (n)](#apidoc.element.sugar.Number.hours)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hoursAfter (n, d, options)](#apidoc.element.sugar.Number.hoursAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hoursAgo (n, d, options)](#apidoc.element.sugar.Number.hoursAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hoursBefore (n, d, options)](#apidoc.element.sugar.Number.hoursBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>hoursFromNow (n, d, options)](#apidoc.element.sugar.Number.hoursFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>isEven (n)](#apidoc.element.sugar.Number.isEven)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>isInteger (n)](#apidoc.element.sugar.Number.isInteger)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>isMultipleOf (n, num)](#apidoc.element.sugar.Number.isMultipleOf)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>isOdd (n)](#apidoc.element.sugar.Number.isOdd)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>log (n, base)](#apidoc.element.sugar.Number.log)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>metric (n, precision, units)](#apidoc.element.sugar.Number.metric)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecond (n)](#apidoc.element.sugar.Number.millisecond)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondAfter (n, d, options)](#apidoc.element.sugar.Number.millisecondAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondAgo (n, d, options)](#apidoc.element.sugar.Number.millisecondAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondBefore (n, d, options)](#apidoc.element.sugar.Number.millisecondBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondFromNow (n, d, options)](#apidoc.element.sugar.Number.millisecondFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>milliseconds (n)](#apidoc.element.sugar.Number.milliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsAfter (n, d, options)](#apidoc.element.sugar.Number.millisecondsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsAgo (n, d, options)](#apidoc.element.sugar.Number.millisecondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsBefore (n, d, options)](#apidoc.element.sugar.Number.millisecondsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsFromNow (n, d, options)](#apidoc.element.sugar.Number.millisecondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minute (n)](#apidoc.element.sugar.Number.minute)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minuteAfter (n, d, options)](#apidoc.element.sugar.Number.minuteAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minuteAgo (n, d, options)](#apidoc.element.sugar.Number.minuteAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minuteBefore (n, d, options)](#apidoc.element.sugar.Number.minuteBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minuteFromNow (n, d, options)](#apidoc.element.sugar.Number.minuteFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minutes (n)](#apidoc.element.sugar.Number.minutes)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minutesAfter (n, d, options)](#apidoc.element.sugar.Number.minutesAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minutesAgo (n, d, options)](#apidoc.element.sugar.Number.minutesAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minutesBefore (n, d, options)](#apidoc.element.sugar.Number.minutesBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>minutesFromNow (n, d, options)](#apidoc.element.sugar.Number.minutesFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>month (n)](#apidoc.element.sugar.Number.month)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthAfter (n, d, options)](#apidoc.element.sugar.Number.monthAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthAgo (n, d, options)](#apidoc.element.sugar.Number.monthAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthBefore (n, d, options)](#apidoc.element.sugar.Number.monthBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthFromNow (n, d, options)](#apidoc.element.sugar.Number.monthFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>months (n)](#apidoc.element.sugar.Number.months)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthsAfter (n, d, options)](#apidoc.element.sugar.Number.monthsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthsAgo (n, d, options)](#apidoc.element.sugar.Number.monthsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthsBefore (n, d, options)](#apidoc.element.sugar.Number.monthsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>monthsFromNow (n, d, options)](#apidoc.element.sugar.Number.monthsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>ordinalize (n)](#apidoc.element.sugar.Number.ordinalize)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>pad (n, place, sign, base)](#apidoc.element.sugar.Number.pad)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>pow (n, arg)](#apidoc.element.sugar.Number.pow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>random (n1, n2)](#apidoc.element.sugar.Number.random)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>range (start, end)](#apidoc.element.sugar.Number.range)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>round (n, precision)](#apidoc.element.sugar.Number.round)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>second (n)](#apidoc.element.sugar.Number.second)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondAfter (n, d, options)](#apidoc.element.sugar.Number.secondAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondAgo (n, d, options)](#apidoc.element.sugar.Number.secondAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondBefore (n, d, options)](#apidoc.element.sugar.Number.secondBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondFromNow (n, d, options)](#apidoc.element.sugar.Number.secondFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>seconds (n)](#apidoc.element.sugar.Number.seconds)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondsAfter (n, d, options)](#apidoc.element.sugar.Number.secondsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondsAgo (n, d, options)](#apidoc.element.sugar.Number.secondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondsBefore (n, d, options)](#apidoc.element.sugar.Number.secondsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>secondsFromNow (n, d, options)](#apidoc.element.sugar.Number.secondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>sin (n, arg)](#apidoc.element.sugar.Number.sin)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>sqrt (n, arg)](#apidoc.element.sugar.Number.sqrt)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>tan (n, arg)](#apidoc.element.sugar.Number.tan)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>times (n, fn)](#apidoc.element.sugar.Number.times)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>toNumber (n)](#apidoc.element.sugar.Number.toNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>upto (n, num, step, fn)](#apidoc.element.sugar.Number.upto)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>week (n)](#apidoc.element.sugar.Number.week)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weekAfter (n, d, options)](#apidoc.element.sugar.Number.weekAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weekAgo (n, d, options)](#apidoc.element.sugar.Number.weekAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weekBefore (n, d, options)](#apidoc.element.sugar.Number.weekBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weekFromNow (n, d, options)](#apidoc.element.sugar.Number.weekFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weeks (n)](#apidoc.element.sugar.Number.weeks)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weeksAfter (n, d, options)](#apidoc.element.sugar.Number.weeksAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weeksAgo (n, d, options)](#apidoc.element.sugar.Number.weeksAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weeksBefore (n, d, options)](#apidoc.element.sugar.Number.weeksBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>weeksFromNow (n, d, options)](#apidoc.element.sugar.Number.weeksFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>year (n)](#apidoc.element.sugar.Number.year)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearAfter (n, d, options)](#apidoc.element.sugar.Number.yearAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearAgo (n, d, options)](#apidoc.element.sugar.Number.yearAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearBefore (n, d, options)](#apidoc.element.sugar.Number.yearBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearFromNow (n, d, options)](#apidoc.element.sugar.Number.yearFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>years (n)](#apidoc.element.sugar.Number.years)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearsAfter (n, d, options)](#apidoc.element.sugar.Number.yearsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearsAgo (n, d, options)](#apidoc.element.sugar.Number.yearsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearsBefore (n, d, options)](#apidoc.element.sugar.Number.yearsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.</span>yearsFromNow (n, d, options)](#apidoc.element.sugar.Number.yearsFromNow)

#### [module sugar.Number.prototype](#apidoc.module.sugar.Number.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Number.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Number.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Number.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Number.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>abbr ()](#apidoc.element.sugar.Number.prototype.abbr)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>abs ()](#apidoc.element.sugar.Number.prototype.abs)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>acos ()](#apidoc.element.sugar.Number.prototype.acos)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>add ()](#apidoc.element.sugar.Number.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>addAll ()](#apidoc.element.sugar.Number.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>asin ()](#apidoc.element.sugar.Number.prototype.asin)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>atan ()](#apidoc.element.sugar.Number.prototype.atan)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>average ()](#apidoc.element.sugar.Number.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>bytes ()](#apidoc.element.sugar.Number.prototype.bytes)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>cap ()](#apidoc.element.sugar.Number.prototype.cap)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>ceil ()](#apidoc.element.sugar.Number.prototype.ceil)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>chr ()](#apidoc.element.sugar.Number.prototype.chr)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>clamp ()](#apidoc.element.sugar.Number.prototype.clamp)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>clone ()](#apidoc.element.sugar.Number.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>cos ()](#apidoc.element.sugar.Number.prototype.cos)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>count ()](#apidoc.element.sugar.Number.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>day ()](#apidoc.element.sugar.Number.prototype.day)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayAfter ()](#apidoc.element.sugar.Number.prototype.dayAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayAgo ()](#apidoc.element.sugar.Number.prototype.dayAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayBefore ()](#apidoc.element.sugar.Number.prototype.dayBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayFromNow ()](#apidoc.element.sugar.Number.prototype.dayFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>days ()](#apidoc.element.sugar.Number.prototype.days)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysAfter ()](#apidoc.element.sugar.Number.prototype.daysAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysAgo ()](#apidoc.element.sugar.Number.prototype.daysAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysBefore ()](#apidoc.element.sugar.Number.prototype.daysBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysFromNow ()](#apidoc.element.sugar.Number.prototype.daysFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>defaults ()](#apidoc.element.sugar.Number.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>downto ()](#apidoc.element.sugar.Number.prototype.downto)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>duration ()](#apidoc.element.sugar.Number.prototype.duration)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>every ()](#apidoc.element.sugar.Number.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>exclude ()](#apidoc.element.sugar.Number.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>exp ()](#apidoc.element.sugar.Number.prototype.exp)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>filter ()](#apidoc.element.sugar.Number.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>find ()](#apidoc.element.sugar.Number.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>floor ()](#apidoc.element.sugar.Number.prototype.floor)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>forEach ()](#apidoc.element.sugar.Number.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>format ()](#apidoc.element.sugar.Number.prototype.format)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>get ()](#apidoc.element.sugar.Number.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>has ()](#apidoc.element.sugar.Number.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Number.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hex ()](#apidoc.element.sugar.Number.prototype.hex)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hour ()](#apidoc.element.sugar.Number.prototype.hour)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourAfter ()](#apidoc.element.sugar.Number.prototype.hourAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourAgo ()](#apidoc.element.sugar.Number.prototype.hourAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourBefore ()](#apidoc.element.sugar.Number.prototype.hourBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourFromNow ()](#apidoc.element.sugar.Number.prototype.hourFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hours ()](#apidoc.element.sugar.Number.prototype.hours)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursAfter ()](#apidoc.element.sugar.Number.prototype.hoursAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursAgo ()](#apidoc.element.sugar.Number.prototype.hoursAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursBefore ()](#apidoc.element.sugar.Number.prototype.hoursBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursFromNow ()](#apidoc.element.sugar.Number.prototype.hoursFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>intersect ()](#apidoc.element.sugar.Number.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>invert ()](#apidoc.element.sugar.Number.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isArguments ()](#apidoc.element.sugar.Number.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isArray ()](#apidoc.element.sugar.Number.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isBoolean ()](#apidoc.element.sugar.Number.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isDate ()](#apidoc.element.sugar.Number.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isEmpty ()](#apidoc.element.sugar.Number.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isEqual ()](#apidoc.element.sugar.Number.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isError ()](#apidoc.element.sugar.Number.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isEven ()](#apidoc.element.sugar.Number.prototype.isEven)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isFunction ()](#apidoc.element.sugar.Number.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isInteger ()](#apidoc.element.sugar.Number.prototype.isInteger)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isMap ()](#apidoc.element.sugar.Number.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isMultipleOf ()](#apidoc.element.sugar.Number.prototype.isMultipleOf)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isNumber ()](#apidoc.element.sugar.Number.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isObject ()](#apidoc.element.sugar.Number.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isOdd ()](#apidoc.element.sugar.Number.prototype.isOdd)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Number.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isRegExp ()](#apidoc.element.sugar.Number.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isSet ()](#apidoc.element.sugar.Number.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isString ()](#apidoc.element.sugar.Number.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>keys ()](#apidoc.element.sugar.Number.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>least ()](#apidoc.element.sugar.Number.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>log ()](#apidoc.element.sugar.Number.prototype.log)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>map ()](#apidoc.element.sugar.Number.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>max ()](#apidoc.element.sugar.Number.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>median ()](#apidoc.element.sugar.Number.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>merge ()](#apidoc.element.sugar.Number.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>mergeAll ()](#apidoc.element.sugar.Number.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>metric ()](#apidoc.element.sugar.Number.prototype.metric)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecond ()](#apidoc.element.sugar.Number.prototype.millisecond)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondAfter ()](#apidoc.element.sugar.Number.prototype.millisecondAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondAgo ()](#apidoc.element.sugar.Number.prototype.millisecondAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondBefore ()](#apidoc.element.sugar.Number.prototype.millisecondBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondFromNow ()](#apidoc.element.sugar.Number.prototype.millisecondFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>milliseconds ()](#apidoc.element.sugar.Number.prototype.milliseconds)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsAfter ()](#apidoc.element.sugar.Number.prototype.millisecondsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsAgo ()](#apidoc.element.sugar.Number.prototype.millisecondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsBefore ()](#apidoc.element.sugar.Number.prototype.millisecondsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsFromNow ()](#apidoc.element.sugar.Number.prototype.millisecondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>min ()](#apidoc.element.sugar.Number.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minute ()](#apidoc.element.sugar.Number.prototype.minute)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteAfter ()](#apidoc.element.sugar.Number.prototype.minuteAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteAgo ()](#apidoc.element.sugar.Number.prototype.minuteAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteBefore ()](#apidoc.element.sugar.Number.prototype.minuteBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteFromNow ()](#apidoc.element.sugar.Number.prototype.minuteFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutes ()](#apidoc.element.sugar.Number.prototype.minutes)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesAfter ()](#apidoc.element.sugar.Number.prototype.minutesAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesAgo ()](#apidoc.element.sugar.Number.prototype.minutesAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesBefore ()](#apidoc.element.sugar.Number.prototype.minutesBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesFromNow ()](#apidoc.element.sugar.Number.prototype.minutesFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>month ()](#apidoc.element.sugar.Number.prototype.month)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthAfter ()](#apidoc.element.sugar.Number.prototype.monthAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthAgo ()](#apidoc.element.sugar.Number.prototype.monthAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthBefore ()](#apidoc.element.sugar.Number.prototype.monthBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthFromNow ()](#apidoc.element.sugar.Number.prototype.monthFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>months ()](#apidoc.element.sugar.Number.prototype.months)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsAfter ()](#apidoc.element.sugar.Number.prototype.monthsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsAgo ()](#apidoc.element.sugar.Number.prototype.monthsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsBefore ()](#apidoc.element.sugar.Number.prototype.monthsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsFromNow ()](#apidoc.element.sugar.Number.prototype.monthsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>most ()](#apidoc.element.sugar.Number.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>none ()](#apidoc.element.sugar.Number.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>ordinalize ()](#apidoc.element.sugar.Number.prototype.ordinalize)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>pad ()](#apidoc.element.sugar.Number.prototype.pad)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>pow ()](#apidoc.element.sugar.Number.prototype.pow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Number.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>reduce ()](#apidoc.element.sugar.Number.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>reject ()](#apidoc.element.sugar.Number.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>remove ()](#apidoc.element.sugar.Number.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>round ()](#apidoc.element.sugar.Number.prototype.round)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>second ()](#apidoc.element.sugar.Number.prototype.second)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondAfter ()](#apidoc.element.sugar.Number.prototype.secondAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondAgo ()](#apidoc.element.sugar.Number.prototype.secondAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondBefore ()](#apidoc.element.sugar.Number.prototype.secondBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondFromNow ()](#apidoc.element.sugar.Number.prototype.secondFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>seconds ()](#apidoc.element.sugar.Number.prototype.seconds)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsAfter ()](#apidoc.element.sugar.Number.prototype.secondsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsAgo ()](#apidoc.element.sugar.Number.prototype.secondsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsBefore ()](#apidoc.element.sugar.Number.prototype.secondsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsFromNow ()](#apidoc.element.sugar.Number.prototype.secondsFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>select ()](#apidoc.element.sugar.Number.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>set ()](#apidoc.element.sugar.Number.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>sin ()](#apidoc.element.sugar.Number.prototype.sin)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>size ()](#apidoc.element.sugar.Number.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>some ()](#apidoc.element.sugar.Number.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>sqrt ()](#apidoc.element.sugar.Number.prototype.sqrt)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>subtract ()](#apidoc.element.sugar.Number.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>sum ()](#apidoc.element.sugar.Number.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>tan ()](#apidoc.element.sugar.Number.prototype.tan)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>tap ()](#apidoc.element.sugar.Number.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>times ()](#apidoc.element.sugar.Number.prototype.times)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toExponential ()](#apidoc.element.sugar.Number.prototype.toExponential)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toFixed ()](#apidoc.element.sugar.Number.prototype.toFixed)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Number.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toNumber ()](#apidoc.element.sugar.Number.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toPrecision ()](#apidoc.element.sugar.Number.prototype.toPrecision)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toQueryString ()](#apidoc.element.sugar.Number.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toString ()](#apidoc.element.sugar.Number.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>upto ()](#apidoc.element.sugar.Number.prototype.upto)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>values ()](#apidoc.element.sugar.Number.prototype.values)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>week ()](#apidoc.element.sugar.Number.prototype.week)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekAfter ()](#apidoc.element.sugar.Number.prototype.weekAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekAgo ()](#apidoc.element.sugar.Number.prototype.weekAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekBefore ()](#apidoc.element.sugar.Number.prototype.weekBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekFromNow ()](#apidoc.element.sugar.Number.prototype.weekFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeks ()](#apidoc.element.sugar.Number.prototype.weeks)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksAfter ()](#apidoc.element.sugar.Number.prototype.weeksAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksAgo ()](#apidoc.element.sugar.Number.prototype.weeksAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksBefore ()](#apidoc.element.sugar.Number.prototype.weeksBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksFromNow ()](#apidoc.element.sugar.Number.prototype.weeksFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>year ()](#apidoc.element.sugar.Number.prototype.year)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearAfter ()](#apidoc.element.sugar.Number.prototype.yearAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearAgo ()](#apidoc.element.sugar.Number.prototype.yearAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearBefore ()](#apidoc.element.sugar.Number.prototype.yearBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearFromNow ()](#apidoc.element.sugar.Number.prototype.yearFromNow)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>years ()](#apidoc.element.sugar.Number.prototype.years)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsAfter ()](#apidoc.element.sugar.Number.prototype.yearsAfter)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsAgo ()](#apidoc.element.sugar.Number.prototype.yearsAgo)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsBefore ()](#apidoc.element.sugar.Number.prototype.yearsBefore)
1.  [function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsFromNow ()](#apidoc.element.sugar.Number.prototype.yearsFromNow)

#### [module sugar.Object](#apidoc.module.sugar.Object)
1.  [function <span class="apidocSignatureSpan">sugar.</span>Object {{signature}}](#apidoc.element.sugar.Object.Object)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>add (obj1, obj2, opts)](#apidoc.element.sugar.Object.add)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>addAll (obj, sources, opts)](#apidoc.element.sugar.Object.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>average (obj, map)](#apidoc.element.sugar.Object.average)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>clone (obj, deep)](#apidoc.element.sugar.Object.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>count (obj, f)](#apidoc.element.sugar.Object.count)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>defaults (target, sources, opts)](#apidoc.element.sugar.Object.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>every (obj, f)](#apidoc.element.sugar.Object.every)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>exclude (obj, f)](#apidoc.element.sugar.Object.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>filter (obj, f)](#apidoc.element.sugar.Object.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>find (obj, f)](#apidoc.element.sugar.Object.find)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>forEach (obj, fn)](#apidoc.element.sugar.Object.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>fromQueryString (obj, options)](#apidoc.element.sugar.Object.fromQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>get (obj, key, any)](#apidoc.element.sugar.Object.get)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>has (obj, key, any)](#apidoc.element.sugar.Object.has)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>intersect (obj1, obj2)](#apidoc.element.sugar.Object.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>invert (obj, multi)](#apidoc.element.sugar.Object.invert)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isArguments (obj)](#apidoc.element.sugar.Object.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isArray ()](#apidoc.element.sugar.Object.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isBoolean (obj)](#apidoc.element.sugar.Object.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isDate (obj, str)](#apidoc.element.sugar.Object.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isEmpty (obj)](#apidoc.element.sugar.Object.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isEqual (obj1, obj2)](#apidoc.element.sugar.Object.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isError (obj, str)](#apidoc.element.sugar.Object.isError)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isFunction (obj, str)](#apidoc.element.sugar.Object.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isMap (obj, str)](#apidoc.element.sugar.Object.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isNumber (obj)](#apidoc.element.sugar.Object.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isObject (obj)](#apidoc.element.sugar.Object.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isRegExp (obj, str)](#apidoc.element.sugar.Object.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isSet (obj, str)](#apidoc.element.sugar.Object.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>isString (obj)](#apidoc.element.sugar.Object.isString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>keys (obj)](#apidoc.element.sugar.Object.keys)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>least (obj, all, map)](#apidoc.element.sugar.Object.least)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>map (obj, map)](#apidoc.element.sugar.Object.map)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>max (obj, all, map)](#apidoc.element.sugar.Object.max)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>median (obj, map)](#apidoc.element.sugar.Object.median)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>merge (target, source, opts)](#apidoc.element.sugar.Object.merge)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>mergeAll (target, sources, opts)](#apidoc.element.sugar.Object.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>min (obj, all, map)](#apidoc.element.sugar.Object.min)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>most (obj, all, map)](#apidoc.element.sugar.Object.most)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>none (obj, f)](#apidoc.element.sugar.Object.none)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>reduce (obj, fn, init)](#apidoc.element.sugar.Object.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>reject (obj, f)](#apidoc.element.sugar.Object.reject)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>remove (obj, f)](#apidoc.element.sugar.Object.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>select (obj, f)](#apidoc.element.sugar.Object.select)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>set (obj, key, val)](#apidoc.element.sugar.Object.set)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>size (obj)](#apidoc.element.sugar.Object.size)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>some (obj, f)](#apidoc.element.sugar.Object.some)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>subtract (obj1, obj2)](#apidoc.element.sugar.Object.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>sum (obj, map)](#apidoc.element.sugar.Object.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>tap (obj, arg)](#apidoc.element.sugar.Object.tap)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>toQueryString (obj, options)](#apidoc.element.sugar.Object.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.</span>values (obj)](#apidoc.element.sugar.Object.values)

#### [module sugar.Object.prototype](#apidoc.module.sugar.Object.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Object.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Object.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Object.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Object.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>add ()](#apidoc.element.sugar.Object.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>addAll ()](#apidoc.element.sugar.Object.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>average ()](#apidoc.element.sugar.Object.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>clone ()](#apidoc.element.sugar.Object.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>count ()](#apidoc.element.sugar.Object.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>defaults ()](#apidoc.element.sugar.Object.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>every ()](#apidoc.element.sugar.Object.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>exclude ()](#apidoc.element.sugar.Object.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>filter ()](#apidoc.element.sugar.Object.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>find ()](#apidoc.element.sugar.Object.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>forEach ()](#apidoc.element.sugar.Object.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>get ()](#apidoc.element.sugar.Object.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>has ()](#apidoc.element.sugar.Object.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Object.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>intersect ()](#apidoc.element.sugar.Object.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>invert ()](#apidoc.element.sugar.Object.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isArguments ()](#apidoc.element.sugar.Object.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isArray ()](#apidoc.element.sugar.Object.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isBoolean ()](#apidoc.element.sugar.Object.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isDate ()](#apidoc.element.sugar.Object.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isEmpty ()](#apidoc.element.sugar.Object.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isEqual ()](#apidoc.element.sugar.Object.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isError ()](#apidoc.element.sugar.Object.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isFunction ()](#apidoc.element.sugar.Object.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isMap ()](#apidoc.element.sugar.Object.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isNumber ()](#apidoc.element.sugar.Object.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isObject ()](#apidoc.element.sugar.Object.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Object.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isRegExp ()](#apidoc.element.sugar.Object.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isSet ()](#apidoc.element.sugar.Object.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isString ()](#apidoc.element.sugar.Object.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>keys ()](#apidoc.element.sugar.Object.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>least ()](#apidoc.element.sugar.Object.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>map ()](#apidoc.element.sugar.Object.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>max ()](#apidoc.element.sugar.Object.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>median ()](#apidoc.element.sugar.Object.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>merge ()](#apidoc.element.sugar.Object.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>mergeAll ()](#apidoc.element.sugar.Object.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>min ()](#apidoc.element.sugar.Object.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>most ()](#apidoc.element.sugar.Object.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>none ()](#apidoc.element.sugar.Object.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Object.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>reduce ()](#apidoc.element.sugar.Object.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>reject ()](#apidoc.element.sugar.Object.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>remove ()](#apidoc.element.sugar.Object.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>select ()](#apidoc.element.sugar.Object.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>set ()](#apidoc.element.sugar.Object.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>size ()](#apidoc.element.sugar.Object.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>some ()](#apidoc.element.sugar.Object.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>subtract ()](#apidoc.element.sugar.Object.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>sum ()](#apidoc.element.sugar.Object.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>tap ()](#apidoc.element.sugar.Object.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Object.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>toQueryString ()](#apidoc.element.sugar.Object.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>toString ()](#apidoc.element.sugar.Object.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>values ()](#apidoc.element.sugar.Object.prototype.values)

#### [module sugar.RegExp](#apidoc.module.sugar.RegExp)
1.  [function <span class="apidocSignatureSpan">sugar.</span>RegExp {{signature}}](#apidoc.element.sugar.RegExp.RegExp)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.</span>addFlags (r, flags)](#apidoc.element.sugar.RegExp.addFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.</span>escape (str)](#apidoc.element.sugar.RegExp.escape)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.</span>getFlags (r)](#apidoc.element.sugar.RegExp.getFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.</span>removeFlags (r, flags)](#apidoc.element.sugar.RegExp.removeFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.</span>setFlags (r, flags)](#apidoc.element.sugar.RegExp.setFlags)

#### [module sugar.RegExp.prototype](#apidoc.module.sugar.RegExp.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.RegExp.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.RegExp.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.RegExp.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.RegExp.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>add ()](#apidoc.element.sugar.RegExp.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>addAll ()](#apidoc.element.sugar.RegExp.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>addFlags ()](#apidoc.element.sugar.RegExp.prototype.addFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>average ()](#apidoc.element.sugar.RegExp.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>clone ()](#apidoc.element.sugar.RegExp.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>compile ()](#apidoc.element.sugar.RegExp.prototype.compile)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>count ()](#apidoc.element.sugar.RegExp.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>defaults ()](#apidoc.element.sugar.RegExp.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>every ()](#apidoc.element.sugar.RegExp.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>exclude ()](#apidoc.element.sugar.RegExp.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>exec ()](#apidoc.element.sugar.RegExp.prototype.exec)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>filter ()](#apidoc.element.sugar.RegExp.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>find ()](#apidoc.element.sugar.RegExp.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>forEach ()](#apidoc.element.sugar.RegExp.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>get ()](#apidoc.element.sugar.RegExp.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>getFlags ()](#apidoc.element.sugar.RegExp.prototype.getFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>has ()](#apidoc.element.sugar.RegExp.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.RegExp.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>intersect ()](#apidoc.element.sugar.RegExp.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>invert ()](#apidoc.element.sugar.RegExp.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isArguments ()](#apidoc.element.sugar.RegExp.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isArray ()](#apidoc.element.sugar.RegExp.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isBoolean ()](#apidoc.element.sugar.RegExp.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isDate ()](#apidoc.element.sugar.RegExp.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isEmpty ()](#apidoc.element.sugar.RegExp.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isEqual ()](#apidoc.element.sugar.RegExp.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isError ()](#apidoc.element.sugar.RegExp.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isFunction ()](#apidoc.element.sugar.RegExp.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isMap ()](#apidoc.element.sugar.RegExp.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isNumber ()](#apidoc.element.sugar.RegExp.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isObject ()](#apidoc.element.sugar.RegExp.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.RegExp.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isRegExp ()](#apidoc.element.sugar.RegExp.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isSet ()](#apidoc.element.sugar.RegExp.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isString ()](#apidoc.element.sugar.RegExp.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>keys ()](#apidoc.element.sugar.RegExp.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>least ()](#apidoc.element.sugar.RegExp.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>map ()](#apidoc.element.sugar.RegExp.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>max ()](#apidoc.element.sugar.RegExp.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>median ()](#apidoc.element.sugar.RegExp.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>merge ()](#apidoc.element.sugar.RegExp.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>mergeAll ()](#apidoc.element.sugar.RegExp.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>min ()](#apidoc.element.sugar.RegExp.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>most ()](#apidoc.element.sugar.RegExp.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>none ()](#apidoc.element.sugar.RegExp.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.RegExp.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>reduce ()](#apidoc.element.sugar.RegExp.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>reject ()](#apidoc.element.sugar.RegExp.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>remove ()](#apidoc.element.sugar.RegExp.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>removeFlags ()](#apidoc.element.sugar.RegExp.prototype.removeFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>select ()](#apidoc.element.sugar.RegExp.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>set ()](#apidoc.element.sugar.RegExp.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>setFlags ()](#apidoc.element.sugar.RegExp.prototype.setFlags)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>size ()](#apidoc.element.sugar.RegExp.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>some ()](#apidoc.element.sugar.RegExp.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>subtract ()](#apidoc.element.sugar.RegExp.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>sum ()](#apidoc.element.sugar.RegExp.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>tap ()](#apidoc.element.sugar.RegExp.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>test ()](#apidoc.element.sugar.RegExp.prototype.test)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>toLocaleString ()](#apidoc.element.sugar.RegExp.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>toQueryString ()](#apidoc.element.sugar.RegExp.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>toString ()](#apidoc.element.sugar.RegExp.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>values ()](#apidoc.element.sugar.RegExp.prototype.values)

#### [module sugar.String](#apidoc.module.sugar.String)
1.  [function <span class="apidocSignatureSpan">sugar.</span>String {{signature}}](#apidoc.element.sugar.String.String)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>at (str, index, loop)](#apidoc.element.sugar.String.at)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>camelize (str, upper)](#apidoc.element.sugar.String.camelize)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>capitalize (str, lower, all)](#apidoc.element.sugar.String.capitalize)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>chars (str, search, fn)](#apidoc.element.sugar.String.chars)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>codes (str, fn)](#apidoc.element.sugar.String.codes)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>compact (str)](#apidoc.element.sugar.String.compact)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>dasherize (str)](#apidoc.element.sugar.String.dasherize)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>decodeBase64 (str)](#apidoc.element.sugar.String.decodeBase64)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>encodeBase64 (str)](#apidoc.element.sugar.String.encodeBase64)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>escapeHTML (str)](#apidoc.element.sugar.String.escapeHTML)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>escapeURL (str, param)](#apidoc.element.sugar.String.escapeURL)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>first (str, num)](#apidoc.element.sugar.String.first)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>forEach (str, search, fn)](#apidoc.element.sugar.String.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>format ()](#apidoc.element.sugar.String.format)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>from (str, from)](#apidoc.element.sugar.String.from)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>includes (a)](#apidoc.element.sugar.String.includes)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>insert (str, substr, index)](#apidoc.element.sugar.String.insert)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>isBlank (str)](#apidoc.element.sugar.String.isBlank)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>isEmpty (str)](#apidoc.element.sugar.String.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>last (str, num)](#apidoc.element.sugar.String.last)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>lines (str, fn)](#apidoc.element.sugar.String.lines)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>pad (str, num, padding)](#apidoc.element.sugar.String.pad)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>padLeft (str, num, padding)](#apidoc.element.sugar.String.padLeft)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>padRight (str, num, padding)](#apidoc.element.sugar.String.padRight)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>parameterize (str, separator)](#apidoc.element.sugar.String.parameterize)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>range (start, end)](#apidoc.element.sugar.String.range)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>remove (str, f)](#apidoc.element.sugar.String.remove)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>removeAll (str, f)](#apidoc.element.sugar.String.removeAll)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>removeTags (str, tag, replace)](#apidoc.element.sugar.String.removeTags)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>replaceAll ()](#apidoc.element.sugar.String.replaceAll)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>reverse (str)](#apidoc.element.sugar.String.reverse)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>shift (str, n)](#apidoc.element.sugar.String.shift)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>spacify (str)](#apidoc.element.sugar.String.spacify)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>stripTags (str, tag, replace)](#apidoc.element.sugar.String.stripTags)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>titleize (str)](#apidoc.element.sugar.String.titleize)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>to (str, to)](#apidoc.element.sugar.String.to)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>toNumber (str, base)](#apidoc.element.sugar.String.toNumber)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>trimLeft (str)](#apidoc.element.sugar.String.trimLeft)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>trimRight (str)](#apidoc.element.sugar.String.trimRight)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>truncate (str, length, from, ellipsis)](#apidoc.element.sugar.String.truncate)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>truncateOnWord (str, length, from, ellipsis)](#apidoc.element.sugar.String.truncateOnWord)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>underscore (str)](#apidoc.element.sugar.String.underscore)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>unescapeHTML (str)](#apidoc.element.sugar.String.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>unescapeURL (str, param)](#apidoc.element.sugar.String.unescapeURL)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>words (str, fn)](#apidoc.element.sugar.String.words)

#### [module sugar.String.includes](#apidoc.module.sugar.String.includes)
1.  [function <span class="apidocSignatureSpan">sugar.String.</span>includes (a)](#apidoc.element.sugar.String.includes.includes)
1.  [function <span class="apidocSignatureSpan">sugar.String.includes.</span>instance (b)](#apidoc.element.sugar.String.includes.instance)
1.  object <span class="apidocSignatureSpan">sugar.String.includes.</span>flags

#### [module sugar.String.prototype](#apidoc.module.sugar.String.prototype)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.String.prototype.__defineGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.String.prototype.__defineSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.String.prototype.__lookupGetter__)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.String.prototype.__lookupSetter__)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>add ()](#apidoc.element.sugar.String.prototype.add)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>addAll ()](#apidoc.element.sugar.String.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>anchor ()](#apidoc.element.sugar.String.prototype.anchor)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>at ()](#apidoc.element.sugar.String.prototype.at)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>average ()](#apidoc.element.sugar.String.prototype.average)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>big ()](#apidoc.element.sugar.String.prototype.big)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>blink ()](#apidoc.element.sugar.String.prototype.blink)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>bold ()](#apidoc.element.sugar.String.prototype.bold)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>camelize ()](#apidoc.element.sugar.String.prototype.camelize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>capitalize ()](#apidoc.element.sugar.String.prototype.capitalize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>charAt ()](#apidoc.element.sugar.String.prototype.charAt)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>charCodeAt ()](#apidoc.element.sugar.String.prototype.charCodeAt)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>chars ()](#apidoc.element.sugar.String.prototype.chars)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>clone ()](#apidoc.element.sugar.String.prototype.clone)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>codePointAt ()](#apidoc.element.sugar.String.prototype.codePointAt)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>codes ()](#apidoc.element.sugar.String.prototype.codes)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>compact ()](#apidoc.element.sugar.String.prototype.compact)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>concat ()](#apidoc.element.sugar.String.prototype.concat)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>count ()](#apidoc.element.sugar.String.prototype.count)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>dasherize ()](#apidoc.element.sugar.String.prototype.dasherize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>decodeBase64 ()](#apidoc.element.sugar.String.prototype.decodeBase64)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>defaults ()](#apidoc.element.sugar.String.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>encodeBase64 ()](#apidoc.element.sugar.String.prototype.encodeBase64)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>endsWith ()](#apidoc.element.sugar.String.prototype.endsWith)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>entityify ()](#apidoc.element.sugar.String.prototype.entityify)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>escapeHTML ()](#apidoc.element.sugar.String.prototype.escapeHTML)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>escapeURL ()](#apidoc.element.sugar.String.prototype.escapeURL)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>every ()](#apidoc.element.sugar.String.prototype.every)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>exclude ()](#apidoc.element.sugar.String.prototype.exclude)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>filter ()](#apidoc.element.sugar.String.prototype.filter)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>find ()](#apidoc.element.sugar.String.prototype.find)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>first ()](#apidoc.element.sugar.String.prototype.first)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>fixed ()](#apidoc.element.sugar.String.prototype.fixed)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>fontcolor ()](#apidoc.element.sugar.String.prototype.fontcolor)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>fontsize ()](#apidoc.element.sugar.String.prototype.fontsize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>forEach ()](#apidoc.element.sugar.String.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>format ()](#apidoc.element.sugar.String.prototype.format)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>from ()](#apidoc.element.sugar.String.prototype.from)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>get ()](#apidoc.element.sugar.String.prototype.get)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>has ()](#apidoc.element.sugar.String.prototype.has)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.String.prototype.hasOwnProperty)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>includes ()](#apidoc.element.sugar.String.prototype.includes)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>indexOf ()](#apidoc.element.sugar.String.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>insert ()](#apidoc.element.sugar.String.prototype.insert)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>intersect ()](#apidoc.element.sugar.String.prototype.intersect)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>invert ()](#apidoc.element.sugar.String.prototype.invert)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isAlpha ()](#apidoc.element.sugar.String.prototype.isAlpha)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isArguments ()](#apidoc.element.sugar.String.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isArray ()](#apidoc.element.sugar.String.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isBlank ()](#apidoc.element.sugar.String.prototype.isBlank)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isBoolean ()](#apidoc.element.sugar.String.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isDate ()](#apidoc.element.sugar.String.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isDigit ()](#apidoc.element.sugar.String.prototype.isDigit)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isEmpty ()](#apidoc.element.sugar.String.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isEqual ()](#apidoc.element.sugar.String.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isError ()](#apidoc.element.sugar.String.prototype.isError)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isFunction ()](#apidoc.element.sugar.String.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isMap ()](#apidoc.element.sugar.String.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isNumber ()](#apidoc.element.sugar.String.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isObject ()](#apidoc.element.sugar.String.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.String.prototype.isPrototypeOf)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isRegExp ()](#apidoc.element.sugar.String.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isSet ()](#apidoc.element.sugar.String.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isString ()](#apidoc.element.sugar.String.prototype.isString)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>italics ()](#apidoc.element.sugar.String.prototype.italics)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>keys ()](#apidoc.element.sugar.String.prototype.keys)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>last ()](#apidoc.element.sugar.String.prototype.last)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>lastIndexOf ()](#apidoc.element.sugar.String.prototype.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>least ()](#apidoc.element.sugar.String.prototype.least)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>lines ()](#apidoc.element.sugar.String.prototype.lines)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>link ()](#apidoc.element.sugar.String.prototype.link)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>localeCompare ()](#apidoc.element.sugar.String.prototype.localeCompare)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>map ()](#apidoc.element.sugar.String.prototype.map)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>match ()](#apidoc.element.sugar.String.prototype.match)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>max ()](#apidoc.element.sugar.String.prototype.max)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>median ()](#apidoc.element.sugar.String.prototype.median)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>merge ()](#apidoc.element.sugar.String.prototype.merge)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>mergeAll ()](#apidoc.element.sugar.String.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>min ()](#apidoc.element.sugar.String.prototype.min)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>most ()](#apidoc.element.sugar.String.prototype.most)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>none ()](#apidoc.element.sugar.String.prototype.none)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>normalize ()](#apidoc.element.sugar.String.prototype.normalize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>pad ()](#apidoc.element.sugar.String.prototype.pad)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>padLeft ()](#apidoc.element.sugar.String.prototype.padLeft)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>padRight ()](#apidoc.element.sugar.String.prototype.padRight)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>parameterize ()](#apidoc.element.sugar.String.prototype.parameterize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.String.prototype.propertyIsEnumerable)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>reduce ()](#apidoc.element.sugar.String.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>reject ()](#apidoc.element.sugar.String.prototype.reject)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>remove ()](#apidoc.element.sugar.String.prototype.remove)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>removeAll ()](#apidoc.element.sugar.String.prototype.removeAll)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>removeTags ()](#apidoc.element.sugar.String.prototype.removeTags)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>repeat ()](#apidoc.element.sugar.String.prototype.repeat)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>replace ()](#apidoc.element.sugar.String.prototype.replace)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>replaceAll ()](#apidoc.element.sugar.String.prototype.replaceAll)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>reverse ()](#apidoc.element.sugar.String.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>search ()](#apidoc.element.sugar.String.prototype.search)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>select ()](#apidoc.element.sugar.String.prototype.select)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>set ()](#apidoc.element.sugar.String.prototype.set)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>shift ()](#apidoc.element.sugar.String.prototype.shift)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>size ()](#apidoc.element.sugar.String.prototype.size)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>slice ()](#apidoc.element.sugar.String.prototype.slice)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>small ()](#apidoc.element.sugar.String.prototype.small)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>some ()](#apidoc.element.sugar.String.prototype.some)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>spacify ()](#apidoc.element.sugar.String.prototype.spacify)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>split ()](#apidoc.element.sugar.String.prototype.split)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>startsWith ()](#apidoc.element.sugar.String.prototype.startsWith)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>strike ()](#apidoc.element.sugar.String.prototype.strike)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>stripTags ()](#apidoc.element.sugar.String.prototype.stripTags)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>sub ()](#apidoc.element.sugar.String.prototype.sub)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>substr ()](#apidoc.element.sugar.String.prototype.substr)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>substring ()](#apidoc.element.sugar.String.prototype.substring)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>subtract ()](#apidoc.element.sugar.String.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>sum ()](#apidoc.element.sugar.String.prototype.sum)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>sup ()](#apidoc.element.sugar.String.prototype.sup)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>supplant ()](#apidoc.element.sugar.String.prototype.supplant)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>tap ()](#apidoc.element.sugar.String.prototype.tap)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>titleize ()](#apidoc.element.sugar.String.prototype.titleize)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>to ()](#apidoc.element.sugar.String.prototype.to)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLocaleLowerCase ()](#apidoc.element.sugar.String.prototype.toLocaleLowerCase)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLocaleString ()](#apidoc.element.sugar.String.prototype.toLocaleString)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLocaleUpperCase ()](#apidoc.element.sugar.String.prototype.toLocaleUpperCase)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLowerCase ()](#apidoc.element.sugar.String.prototype.toLowerCase)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toNumber ()](#apidoc.element.sugar.String.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toQueryString ()](#apidoc.element.sugar.String.prototype.toQueryString)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toString ()](#apidoc.element.sugar.String.prototype.toString)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toUpperCase ()](#apidoc.element.sugar.String.prototype.toUpperCase)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>trim ()](#apidoc.element.sugar.String.prototype.trim)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>trimLeft ()](#apidoc.element.sugar.String.prototype.trimLeft)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>trimRight ()](#apidoc.element.sugar.String.prototype.trimRight)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>truncate ()](#apidoc.element.sugar.String.prototype.truncate)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>truncateOnWord ()](#apidoc.element.sugar.String.prototype.truncateOnWord)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>underscore ()](#apidoc.element.sugar.String.prototype.underscore)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>unescapeHTML ()](#apidoc.element.sugar.String.prototype.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>unescapeURL ()](#apidoc.element.sugar.String.prototype.unescapeURL)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>values ()](#apidoc.element.sugar.String.prototype.values)
1.  [function <span class="apidocSignatureSpan">sugar.String.prototype.</span>words ()](#apidoc.element.sugar.String.prototype.words)



# <a name="apidoc.module.sugar"></a>[module sugar](#apidoc.module.sugar)

#### <a name="apidoc.element.sugar.Array"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array {{signature}}](#apidoc.element.sugar.Array)
- description and source-code
```javascript
SugarArray
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.count"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.count (a)](#apidoc.element.sugar.Array.count)
- description and source-code
```javascript
Array.count = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.every"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.every (a)](#apidoc.element.sugar.Array.every)
- description and source-code
```javascript
Array.every = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.filter"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.filter (a)](#apidoc.element.sugar.Array.filter)
- description and source-code
```javascript
Array.filter = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.find"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.find (a)](#apidoc.element.sugar.Array.find)
- description and source-code
```javascript
Array.find = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.findIndex"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.findIndex (a)](#apidoc.element.sugar.Array.findIndex)
- description and source-code
```javascript
Array.findIndex = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.map"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.map (a)](#apidoc.element.sugar.Array.map)
- description and source-code
```javascript
Array.map = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.none"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.none (a)](#apidoc.element.sugar.Array.none)
- description and source-code
```javascript
Array.none = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.some"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array.some (a)](#apidoc.element.sugar.Array.some)
- description and source-code
```javascript
Array.some = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date"></a>[function <span class="apidocSignatureSpan">sugar.</span>Date {{signature}}](#apidoc.element.sugar.Date)
- description and source-code
```javascript
SugarDate
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function"></a>[function <span class="apidocSignatureSpan">sugar.</span>Function {{signature}}](#apidoc.element.sugar.Function)
- description and source-code
```javascript
SugarFunction
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number"></a>[function <span class="apidocSignatureSpan">sugar.</span>Number {{signature}}](#apidoc.element.sugar.Number)
- description and source-code
```javascript
SugarNumber
```
- example usage
```shell
...
  },
  'cube': function (n) {
    return n * n * n;
  }
});

Sugar.Number.square(3);         // 9
new Sugar.Number(5).cube().raw; // 125
Sugar.Number.randomish()        // ???

Sugar.extend();
(2).square();       // 4
(4).cube();         // 64
Number.randomish(); // ???
...
```

#### <a name="apidoc.element.sugar.Object"></a>[function <span class="apidocSignatureSpan">sugar.</span>Object {{signature}}](#apidoc.element.sugar.Object)
- description and source-code
```javascript
SugarObject
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp"></a>[function <span class="apidocSignatureSpan">sugar.</span>RegExp {{signature}}](#apidoc.element.sugar.RegExp)
- description and source-code
```javascript
SugarRegExp
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String"></a>[function <span class="apidocSignatureSpan">sugar.</span>String {{signature}}](#apidoc.element.sugar.String)
- description and source-code
```javascript
SugarString
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.includes"></a>[function <span class="apidocSignatureSpan">sugar.</span>String.includes (a)](#apidoc.element.sugar.String.includes)
- description and source-code
```javascript
String.includes = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array"></a>[module sugar.Array](#apidoc.module.sugar.Array)

#### <a name="apidoc.element.sugar.Array.Array"></a>[function <span class="apidocSignatureSpan">sugar.</span>Array {{signature}}](#apidoc.element.sugar.Array.Array)
- description and source-code
```javascript
SugarArray
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.add"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>add (arr, item, index)](#apidoc.element.sugar.Array.add)
- description and source-code
```javascript
add = function (arr, item, index) {
  return arrayAppend(arrayClone(arr), item, index);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Array.append"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>append (arr, item, index)](#apidoc.element.sugar.Array.append)
- description and source-code
```javascript
append = function (arr, item, index) {
  return arrayAppend(arr, item, index);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.at"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>at (arr, index, loop)](#apidoc.element.sugar.Array.at)
- description and source-code
```javascript
at = function (arr, index, loop) {
  return getEntriesForIndexes(arr, index, loop);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.average"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>average (arr, map)](#apidoc.element.sugar.Array.average)
- description and source-code
```javascript
average = function (arr, map) {
  return average(arr, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.clone"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>clone (arr)](#apidoc.element.sugar.Array.clone)
- description and source-code
```javascript
clone = function (arr) {
  return arrayClone(arr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.compact"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>compact (arr, all)](#apidoc.element.sugar.Array.compact)
- description and source-code
```javascript
compact = function (arr, all) {
  return arrayCompact(arr, all);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.construct"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>construct (n, fn)](#apidoc.element.sugar.Array.construct)
- description and source-code
```javascript
construct = function (n, fn) {
  n = coercePositiveInteger(n);
  return Array.from(new Array(n), function(el, i) {
    return fn && fn(i);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.count"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>count (a)](#apidoc.element.sugar.Array.count)
- description and source-code
```javascript
count = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.create"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>create (obj, clone)](#apidoc.element.sugar.Array.create)
- description and source-code
```javascript
create = function (obj, clone) {
  return arrayCreate(obj, clone);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.every"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>every (a)](#apidoc.element.sugar.Array.every)
- description and source-code
```javascript
every = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.everyFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>everyFromIndex ()](#apidoc.element.sugar.Array.everyFromIndex)
- description and source-code
```javascript
everyFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>exclude (arr, f)](#apidoc.element.sugar.Array.exclude)
- description and source-code
```javascript
exclude = function (arr, f) {
  return arrayExclude(arr, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.filter"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>filter (a)](#apidoc.element.sugar.Array.filter)
- description and source-code
```javascript
filter = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.filterFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>filterFromIndex ()](#apidoc.element.sugar.Array.filterFromIndex)
- description and source-code
```javascript
filterFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.find"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>find (a)](#apidoc.element.sugar.Array.find)
- description and source-code
```javascript
find = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.findFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>findFromIndex ()](#apidoc.element.sugar.Array.findFromIndex)
- description and source-code
```javascript
findFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.findIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>findIndex (a)](#apidoc.element.sugar.Array.findIndex)
- description and source-code
```javascript
findIndex = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.findIndexFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>findIndexFromIndex ()](#apidoc.element.sugar.Array.findIndexFromIndex)
- description and source-code
```javascript
findIndexFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.first"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>first (arr, num)](#apidoc.element.sugar.Array.first)
- description and source-code
```javascript
first = function (arr, num) {
  if (isUndefined(num)) return arr[0];
  if (num < 0) num = 0;
  return arr.slice(0, num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.flatten"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>flatten (arr, limit)](#apidoc.element.sugar.Array.flatten)
- description and source-code
```javascript
flatten = function (arr, limit) {
  return arrayFlatten(arr, limit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.forEachFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>forEachFromIndex ()](#apidoc.element.sugar.Array.forEachFromIndex)
- description and source-code
```javascript
forEachFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.from"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>from (arr, num)](#apidoc.element.sugar.Array.from)
- description and source-code
```javascript
from = function (arr, num) {
  return arr.slice(num);
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
    coercePositiveInteger = require('../common/internal/coercePositiveInteger');

Sugar.Array.defineStatic({

  'construct': function(n, fn) {
    n = coercePositiveInteger(n);
    return Array.from(new Array(n), function(el, i) {
      return fn && fn(i);
    });
  }

});

module.exports = Sugar.Array.construct;
...
```

#### <a name="apidoc.element.sugar.Array.groupBy"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>groupBy (arr, map, fn)](#apidoc.element.sugar.Array.groupBy)
- description and source-code
```javascript
groupBy = function (arr, map, fn) {
  return arrayGroupBy(arr, map, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.inGroups"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>inGroups (arr, num, padding)](#apidoc.element.sugar.Array.inGroups)
- description and source-code
```javascript
inGroups = function (arr, num, padding) {
  var pad = isDefined(padding);
  var result = new Array(num);
  var divisor = ceil(arr.length / num);
  simpleRepeat(num, function(i) {
    var index = i * divisor;
    var group = arr.slice(index, index + divisor);
    if (pad && group.length < divisor) {
      simpleRepeat(divisor - group.length, function() {
        group.push(padding);
      });
    }
    result[i] = group;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.inGroupsOf"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>inGroupsOf (arr, num, padding)](#apidoc.element.sugar.Array.inGroupsOf)
- description and source-code
```javascript
inGroupsOf = function (arr, num, padding) {
  var result = [], len = arr.length, group;
  if (len === 0 || num === 0) return arr;
  if (isUndefined(num)) num = 1;
  if (isUndefined(padding)) padding = null;
  simpleRepeat(ceil(len / num), function(i) {
    group = arr.slice(num * i, num * i + num);
    while(group.length < num) {
      group.push(padding);
    }
    result.push(group);
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.insert"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>insert (arr, item, index)](#apidoc.element.sugar.Array.insert)
- description and source-code
```javascript
insert = function (arr, item, index) {
  return arrayAppend(arr, item, index);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>intersect (arr1, arr2)](#apidoc.element.sugar.Array.intersect)
- description and source-code
```javascript
intersect = function (arr1, arr2) {
  return arrayIntersectOrSubtract(arr1, arr2, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>isEmpty (arr)](#apidoc.element.sugar.Array.isEmpty)
- description and source-code
```javascript
isEmpty = function (arr) {
  return arr.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>isEqual (a, b)](#apidoc.element.sugar.Array.isEqual)
- description and source-code
```javascript
isEqual = function (a, b) {
  return isEqual(a, b);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.last"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>last (arr, num)](#apidoc.element.sugar.Array.last)
- description and source-code
```javascript
last = function (arr, num) {
  if (isUndefined(num)) return arr[arr.length - 1];
  var start = arr.length - num < 0 ? 0 : arr.length - num;
  return arr.slice(start);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.least"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>least (arr, all, map)](#apidoc.element.sugar.Array.least)
- description and source-code
```javascript
least = function (arr, all, map) {
  return getLeastOrMost(arr, all, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.map"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>map (a)](#apidoc.element.sugar.Array.map)
- description and source-code
```javascript
map = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.mapFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>mapFromIndex ()](#apidoc.element.sugar.Array.mapFromIndex)
- description and source-code
```javascript
mapFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.max"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>max (arr, all, map)](#apidoc.element.sugar.Array.max)
- description and source-code
```javascript
max = function (arr, all, map) {
  return getMinOrMax(arr, all, map, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.median"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>median (arr, map)](#apidoc.element.sugar.Array.median)
- description and source-code
```javascript
median = function (arr, map) {
  return median(arr, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.min"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>min (arr, all, map)](#apidoc.element.sugar.Array.min)
- description and source-code
```javascript
min = function (arr, all, map) {
  return getMinOrMax(arr, all, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.most"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>most (arr, all, map)](#apidoc.element.sugar.Array.most)
- description and source-code
```javascript
most = function (arr, all, map) {
  return getLeastOrMost(arr, all, map, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.none"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>none (a)](#apidoc.element.sugar.Array.none)
- description and source-code
```javascript
none = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.reduceFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>reduceFromIndex ()](#apidoc.element.sugar.Array.reduceFromIndex)
- description and source-code
```javascript
reduceFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.reduceRightFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>reduceRightFromIndex ()](#apidoc.element.sugar.Array.reduceRightFromIndex)
- description and source-code
```javascript
reduceRightFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.remove"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>remove (arr, f)](#apidoc.element.sugar.Array.remove)
- description and source-code
```javascript
remove = function (arr, f) {
  return arrayRemove(arr, f);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Array.removeAt"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>removeAt (arr, start, end)](#apidoc.element.sugar.Array.removeAt)
- description and source-code
```javascript
removeAt = function (arr, start, end) {
  if (isUndefined(start)) return arr;
  if (isUndefined(end))   end = start;
  arr.splice(start, end - start + 1);
  return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.sample"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>sample (arr, arg1, arg2)](#apidoc.element.sugar.Array.sample)
- description and source-code
```javascript
sample = function (arr, arg1, arg2) {
  var result = [], num, remove, single;
  if (isBoolean(arg1)) {
    remove = arg1;
  } else {
    num = arg1;
    remove = arg2;
  }
  if (isUndefined(num)) {
    num = 1;
    single = true;
  }
  if (!remove) {
    arr = arrayClone(arr);
  }
  num = min(num, arr.length);
  for (var i = 0, index; i < num; i++) {
    index = trunc(Math.random() * arr.length);
    result.push(arr[index]);
    arr.splice(index, 1);
  }
  return single ? result[0] : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.shuffle"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>shuffle (arr)](#apidoc.element.sugar.Array.shuffle)
- description and source-code
```javascript
shuffle = function (arr) {
  return arrayShuffle(arr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.some"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>some (a)](#apidoc.element.sugar.Array.some)
- description and source-code
```javascript
some = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.someFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>someFromIndex ()](#apidoc.element.sugar.Array.someFromIndex)
- description and source-code
```javascript
someFromIndex = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.sortBy"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>sortBy (arr, map, desc)](#apidoc.element.sugar.Array.sortBy)
- description and source-code
```javascript
sortBy = function (arr, map, desc) {
  arr.sort(function(a, b) {
    var aProperty = mapWithShortcuts(a, map, arr, [a]);
    var bProperty = mapWithShortcuts(b, map, arr, [b]);
    return compareValue(aProperty, bProperty) * (desc ? -1 : 1);
  });
  return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>subtract (arr, item)](#apidoc.element.sugar.Array.subtract)
- description and source-code
```javascript
subtract = function (arr, item) {
  return arrayIntersectOrSubtract(arr, item, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.sum"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>sum (arr, map)](#apidoc.element.sugar.Array.sum)
- description and source-code
```javascript
sum = function (arr, map) {
  return sum(arr, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.to"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>to (arr, num)](#apidoc.element.sugar.Array.to)
- description and source-code
```javascript
to = function (arr, num) {
  if (isUndefined(num)) num = arr.length;
  return arr.slice(0, num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.union"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>union (arr1, arr2)](#apidoc.element.sugar.Array.union)
- description and source-code
```javascript
union = function (arr1, arr2) {
  return arrayUnique(arrayConcat(arr1, arr2));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.unique"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>unique (arr, map)](#apidoc.element.sugar.Array.unique)
- description and source-code
```javascript
unique = function (arr, map) {
  return arrayUnique(arr, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.zip"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>zip ()](#apidoc.element.sugar.Array.zip)
- description and source-code
```javascript
zip = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.count"></a>[module sugar.Array.count](#apidoc.module.sugar.Array.count)

#### <a name="apidoc.element.sugar.Array.count.count"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>count (a)](#apidoc.element.sugar.Array.count.count)
- description and source-code
```javascript
count = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.count.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.count.</span>instance (b)](#apidoc.element.sugar.Array.count.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.every"></a>[module sugar.Array.every](#apidoc.module.sugar.Array.every)

#### <a name="apidoc.element.sugar.Array.every.every"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>every (a)](#apidoc.element.sugar.Array.every.every)
- description and source-code
```javascript
every = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.every.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.every.</span>instance (b)](#apidoc.element.sugar.Array.every.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.filter"></a>[module sugar.Array.filter](#apidoc.module.sugar.Array.filter)

#### <a name="apidoc.element.sugar.Array.filter.filter"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>filter (a)](#apidoc.element.sugar.Array.filter.filter)
- description and source-code
```javascript
filter = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.filter.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.filter.</span>instance (b)](#apidoc.element.sugar.Array.filter.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.find"></a>[module sugar.Array.find](#apidoc.module.sugar.Array.find)

#### <a name="apidoc.element.sugar.Array.find.find"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>find (a)](#apidoc.element.sugar.Array.find.find)
- description and source-code
```javascript
find = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.find.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.find.</span>instance (b)](#apidoc.element.sugar.Array.find.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.findIndex"></a>[module sugar.Array.findIndex](#apidoc.module.sugar.Array.findIndex)

#### <a name="apidoc.element.sugar.Array.findIndex.findIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>findIndex (a)](#apidoc.element.sugar.Array.findIndex.findIndex)
- description and source-code
```javascript
findIndex = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.findIndex.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.findIndex.</span>instance (b)](#apidoc.element.sugar.Array.findIndex.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.map"></a>[module sugar.Array.map](#apidoc.module.sugar.Array.map)

#### <a name="apidoc.element.sugar.Array.map.map"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>map (a)](#apidoc.element.sugar.Array.map.map)
- description and source-code
```javascript
map = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.map.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.map.</span>instance (b)](#apidoc.element.sugar.Array.map.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.none"></a>[module sugar.Array.none](#apidoc.module.sugar.Array.none)

#### <a name="apidoc.element.sugar.Array.none.none"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>none (a)](#apidoc.element.sugar.Array.none.none)
- description and source-code
```javascript
none = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.none.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.none.</span>instance (b)](#apidoc.element.sugar.Array.none.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.prototype"></a>[module sugar.Array.prototype](#apidoc.module.sugar.Array.prototype)

#### <a name="apidoc.element.sugar.Array.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Array.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Array.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Array.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Array.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>add ()](#apidoc.element.sugar.Array.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>addAll ()](#apidoc.element.sugar.Array.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.append"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>append ()](#apidoc.element.sugar.Array.prototype.append)
- description and source-code
```javascript
append = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.at"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>at ()](#apidoc.element.sugar.Array.prototype.at)
- description and source-code
```javascript
at = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>average ()](#apidoc.element.sugar.Array.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>clone ()](#apidoc.element.sugar.Array.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.compact"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>compact ()](#apidoc.element.sugar.Array.prototype.compact)
- description and source-code
```javascript
compact = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.concat"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>concat ()](#apidoc.element.sugar.Array.prototype.concat)
- description and source-code
```javascript
concat = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
    map = require('../common/internal/map');

Sugar.Array.defineInstanceWithArguments({

  'zip': function(arr, args) {
    return map(arr, function(el, i) {
      return [el].concat(map(args, function(k) {
        return (i in k) ? k[i] : null;
      }));
    });
  }

});
...
```

#### <a name="apidoc.element.sugar.Array.prototype.copyWithin"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>copyWithin ()](#apidoc.element.sugar.Array.prototype.copyWithin)
- description and source-code
```javascript
copyWithin = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>count ()](#apidoc.element.sugar.Array.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>defaults ()](#apidoc.element.sugar.Array.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.entries"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>entries ()](#apidoc.element.sugar.Array.prototype.entries)
- description and source-code
```javascript
entries = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>every ()](#apidoc.element.sugar.Array.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.everyFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>everyFromIndex ()](#apidoc.element.sugar.Array.prototype.everyFromIndex)
- description and source-code
```javascript
everyFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>exclude ()](#apidoc.element.sugar.Array.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.fill"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>fill ()](#apidoc.element.sugar.Array.prototype.fill)
- description and source-code
```javascript
fill = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>filter ()](#apidoc.element.sugar.Array.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.filterFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>filterFromIndex ()](#apidoc.element.sugar.Array.prototype.filterFromIndex)
- description and source-code
```javascript
filterFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>find ()](#apidoc.element.sugar.Array.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.findFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>findFromIndex ()](#apidoc.element.sugar.Array.prototype.findFromIndex)
- description and source-code
```javascript
findFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.findIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>findIndex ()](#apidoc.element.sugar.Array.prototype.findIndex)
- description and source-code
```javascript
findIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.findIndexFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>findIndexFromIndex ()](#apidoc.element.sugar.Array.prototype.findIndexFromIndex)
- description and source-code
```javascript
findIndexFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.first"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>first ()](#apidoc.element.sugar.Array.prototype.first)
- description and source-code
```javascript
first = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.flatten"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>flatten ()](#apidoc.element.sugar.Array.prototype.flatten)
- description and source-code
```javascript
flatten = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>forEach ()](#apidoc.element.sugar.Array.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.forEachFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>forEachFromIndex ()](#apidoc.element.sugar.Array.prototype.forEachFromIndex)
- description and source-code
```javascript
forEachFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.from"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>from ()](#apidoc.element.sugar.Array.prototype.from)
- description and source-code
```javascript
from = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
    coercePositiveInteger = require('../common/internal/coercePositiveInteger');

Sugar.Array.defineStatic({

  'construct': function(n, fn) {
    n = coercePositiveInteger(n);
    return Array.from(new Array(n), function(el, i) {
      return fn && fn(i);
    });
  }

});

module.exports = Sugar.Array.construct;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>get ()](#apidoc.element.sugar.Array.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.groupBy"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>groupBy ()](#apidoc.element.sugar.Array.prototype.groupBy)
- description and source-code
```javascript
groupBy = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>has ()](#apidoc.element.sugar.Array.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Array.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.inGroups"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>inGroups ()](#apidoc.element.sugar.Array.prototype.inGroups)
- description and source-code
```javascript
inGroups = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.inGroupsOf"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>inGroupsOf ()](#apidoc.element.sugar.Array.prototype.inGroupsOf)
- description and source-code
```javascript
inGroupsOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.includes"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>includes ()](#apidoc.element.sugar.Array.prototype.includes)
- description and source-code
```javascript
includes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>indexOf ()](#apidoc.element.sugar.Array.prototype.indexOf)
- description and source-code
```javascript
indexOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.insert"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>insert ()](#apidoc.element.sugar.Array.prototype.insert)
- description and source-code
```javascript
insert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>intersect ()](#apidoc.element.sugar.Array.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>invert ()](#apidoc.element.sugar.Array.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isArguments ()](#apidoc.element.sugar.Array.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isArray ()](#apidoc.element.sugar.Array.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isBoolean ()](#apidoc.element.sugar.Array.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isDate ()](#apidoc.element.sugar.Array.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isEmpty ()](#apidoc.element.sugar.Array.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isEqual ()](#apidoc.element.sugar.Array.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isError ()](#apidoc.element.sugar.Array.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isFunction ()](#apidoc.element.sugar.Array.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isMap ()](#apidoc.element.sugar.Array.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isNumber ()](#apidoc.element.sugar.Array.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isObject ()](#apidoc.element.sugar.Array.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Array.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isRegExp ()](#apidoc.element.sugar.Array.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isSet ()](#apidoc.element.sugar.Array.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>isString ()](#apidoc.element.sugar.Array.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.join"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>join ()](#apidoc.element.sugar.Array.prototype.join)
- description and source-code
```javascript
join = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>keys ()](#apidoc.element.sugar.Array.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.last"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>last ()](#apidoc.element.sugar.Array.prototype.last)
- description and source-code
```javascript
last = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.lastIndexOf"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>lastIndexOf ()](#apidoc.element.sugar.Array.prototype.lastIndexOf)
- description and source-code
```javascript
lastIndexOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>least ()](#apidoc.element.sugar.Array.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>map ()](#apidoc.element.sugar.Array.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.mapFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>mapFromIndex ()](#apidoc.element.sugar.Array.prototype.mapFromIndex)
- description and source-code
```javascript
mapFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>max ()](#apidoc.element.sugar.Array.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>median ()](#apidoc.element.sugar.Array.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>merge ()](#apidoc.element.sugar.Array.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>mergeAll ()](#apidoc.element.sugar.Array.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>min ()](#apidoc.element.sugar.Array.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>most ()](#apidoc.element.sugar.Array.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>none ()](#apidoc.element.sugar.Array.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.pop"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>pop ()](#apidoc.element.sugar.Array.prototype.pop)
- description and source-code
```javascript
pop = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Array.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.push"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>push ()](#apidoc.element.sugar.Array.prototype.push)
- description and source-code
```javascript
push = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  var result = new Array(num);
  var divisor = ceil(arr.length / num);
  simpleRepeat(num, function(i) {
    var index = i * divisor;
    var group = arr.slice(index, index + divisor);
    if (pad && group.length < divisor) {
      simpleRepeat(divisor - group.length, function() {
        group.push(padding);
      });
    }
    result[i] = group;
  });
  return result;
}
...
```

#### <a name="apidoc.element.sugar.Array.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduce ()](#apidoc.element.sugar.Array.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.reduceFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduceFromIndex ()](#apidoc.element.sugar.Array.prototype.reduceFromIndex)
- description and source-code
```javascript
reduceFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.reduceRight"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduceRight ()](#apidoc.element.sugar.Array.prototype.reduceRight)
- description and source-code
```javascript
reduceRight = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.reduceRightFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reduceRightFromIndex ()](#apidoc.element.sugar.Array.prototype.reduceRightFromIndex)
- description and source-code
```javascript
reduceRightFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reject ()](#apidoc.element.sugar.Array.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>remove ()](#apidoc.element.sugar.Array.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.removeAt"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>removeAt ()](#apidoc.element.sugar.Array.prototype.removeAt)
- description and source-code
```javascript
removeAt = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.reverse"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>reverse ()](#apidoc.element.sugar.Array.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.sample"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sample ()](#apidoc.element.sugar.Array.prototype.sample)
- description and source-code
```javascript
sample = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>select ()](#apidoc.element.sugar.Array.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>set ()](#apidoc.element.sugar.Array.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.shift"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>shift ()](#apidoc.element.sugar.Array.prototype.shift)
- description and source-code
```javascript
shift = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.shuffle"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>shuffle ()](#apidoc.element.sugar.Array.prototype.shuffle)
- description and source-code
```javascript
shuffle = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>size ()](#apidoc.element.sugar.Array.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.slice"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>slice ()](#apidoc.element.sugar.Array.prototype.slice)
- description and source-code
```javascript
slice = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    isUndefined = require('../common/internal/isUndefined');

Sugar.Array.defineInstance({

  'first': function(arr, num) {
    if (isUndefined(num)) return arr[0];
    if (num < 0) num = 0;
    return arr.slice(0, num);
  }

});

module.exports = Sugar.Array.first;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>some ()](#apidoc.element.sugar.Array.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.someFromIndex"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>someFromIndex ()](#apidoc.element.sugar.Array.prototype.someFromIndex)
- description and source-code
```javascript
someFromIndex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.sort"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sort ()](#apidoc.element.sugar.Array.prototype.sort)
- description and source-code
```javascript
sort = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
  compareValue = require('./internal/compareValue'),
  mapWithShortcuts = require('../common/internal/mapWithShortcuts');

Sugar.Array.defineInstance({

'sortBy': function(arr, map, desc) {
  arr.sort(function(a, b) {
    var aProperty = mapWithShortcuts(a, map, arr, [a]);
    var bProperty = mapWithShortcuts(b, map, arr, [b]);
    return compareValue(aProperty, bProperty) * (desc ? -1 : 1);
  });
  return arr;
}
...
```

#### <a name="apidoc.element.sugar.Array.prototype.sortBy"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sortBy ()](#apidoc.element.sugar.Array.prototype.sortBy)
- description and source-code
```javascript
sortBy = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.splice"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>splice ()](#apidoc.element.sugar.Array.prototype.splice)
- description and source-code
```javascript
splice = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    isUndefined = require('../common/internal/isUndefined');

Sugar.Array.defineInstance({

  'removeAt': function(arr, start, end) {
    if (isUndefined(start)) return arr;
    if (isUndefined(end))   end = start;
    arr.splice(start, end - start + 1);
    return arr;
  }

});

module.exports = Sugar.Array.removeAt;
...
```

#### <a name="apidoc.element.sugar.Array.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>subtract ()](#apidoc.element.sugar.Array.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>sum ()](#apidoc.element.sugar.Array.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>tap ()](#apidoc.element.sugar.Array.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.to"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>to ()](#apidoc.element.sugar.Array.prototype.to)
- description and source-code
```javascript
to = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Array.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>toQueryString ()](#apidoc.element.sugar.Array.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>toString ()](#apidoc.element.sugar.Array.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.Array.prototype.union"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>union ()](#apidoc.element.sugar.Array.prototype.union)
- description and source-code
```javascript
union = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.unique"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>unique ()](#apidoc.element.sugar.Array.prototype.unique)
- description and source-code
```javascript
unique = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.unshift"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>unshift ()](#apidoc.element.sugar.Array.prototype.unshift)
- description and source-code
```javascript
unshift = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>values ()](#apidoc.element.sugar.Array.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.prototype.zip"></a>[function <span class="apidocSignatureSpan">sugar.Array.prototype.</span>zip ()](#apidoc.element.sugar.Array.prototype.zip)
- description and source-code
```javascript
zip = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Array.some"></a>[module sugar.Array.some](#apidoc.module.sugar.Array.some)

#### <a name="apidoc.element.sugar.Array.some.some"></a>[function <span class="apidocSignatureSpan">sugar.Array.</span>some (a)](#apidoc.element.sugar.Array.some.some)
- description and source-code
```javascript
some = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Array.some.instance"></a>[function <span class="apidocSignatureSpan">sugar.Array.some.</span>instance (b)](#apidoc.element.sugar.Array.some.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Date"></a>[module sugar.Date](#apidoc.module.sugar.Date)

#### <a name="apidoc.element.sugar.Date.Date"></a>[function <span class="apidocSignatureSpan">sugar.</span>Date {{signature}}](#apidoc.element.sugar.Date.Date)
- description and source-code
```javascript
SugarDate
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addDays"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addDays (d, num, reset)](#apidoc.element.sugar.Date.addDays)
- description and source-code
```javascript
addDays = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addHours"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addHours (d, num, reset)](#apidoc.element.sugar.Date.addHours)
- description and source-code
```javascript
addHours = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addLocale"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addLocale (code, set)](#apidoc.element.sugar.Date.addLocale)
- description and source-code
```javascript
addLocale = function (code, set) {
  return localeManager.add(code, set);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addMilliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addMilliseconds (d, num, reset)](#apidoc.element.sugar.Date.addMilliseconds)
- description and source-code
```javascript
addMilliseconds = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addMinutes"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addMinutes (d, num, reset)](#apidoc.element.sugar.Date.addMinutes)
- description and source-code
```javascript
addMinutes = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addMonths"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addMonths (d, num, reset)](#apidoc.element.sugar.Date.addMonths)
- description and source-code
```javascript
addMonths = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addSeconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addSeconds (d, num, reset)](#apidoc.element.sugar.Date.addSeconds)
- description and source-code
```javascript
addSeconds = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addWeeks"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addWeeks (d, num, reset)](#apidoc.element.sugar.Date.addWeeks)
- description and source-code
```javascript
addWeeks = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.addYears"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>addYears (d, num, reset)](#apidoc.element.sugar.Date.addYears)
- description and source-code
```javascript
addYears = function (d, num, reset) {
  return advanceDate(d, name, num, reset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.advance"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>advance ()](#apidoc.element.sugar.Date.advance)
- description and source-code
```javascript
advance = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.beginningOfDay"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfDay (d, localeCode)](#apidoc.element.sugar.Date.beginningOfDay)
- description and source-code
```javascript
beginningOfDay = function (d, localeCode) {
  return moveToBeginningOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.beginningOfISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfISOWeek (date)](#apidoc.element.sugar.Date.beginningOfISOWeek)
- description and source-code
```javascript
beginningOfISOWeek = function (date) {
  var day = getWeekday(date);
  if (day === 0) {
    day = -6;
  } else if (day !== 1) {
    day = 1;
  }
  setWeekday(date, day);
  return resetTime(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.beginningOfMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfMonth (d, localeCode)](#apidoc.element.sugar.Date.beginningOfMonth)
- description and source-code
```javascript
beginningOfMonth = function (d, localeCode) {
  return moveToBeginningOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.beginningOfWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfWeek (d, localeCode)](#apidoc.element.sugar.Date.beginningOfWeek)
- description and source-code
```javascript
beginningOfWeek = function (d, localeCode) {
  return moveToBeginningOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.beginningOfYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>beginningOfYear (d, localeCode)](#apidoc.element.sugar.Date.beginningOfYear)
- description and source-code
```javascript
beginningOfYear = function (d, localeCode) {
  return moveToBeginningOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.clone"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>clone (date)](#apidoc.element.sugar.Date.clone)
- description and source-code
```javascript
clone = function (date) {
  return cloneDate(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.create"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>create (d, options)](#apidoc.element.sugar.Date.create)
- description and source-code
```javascript
create = function (d, options) {
  return createDate(d, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.daysAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>daysAgo (date, d, options)](#apidoc.element.sugar.Date.daysAgo)
- description and source-code
```javascript
daysAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.daysFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>daysFromNow (date, d, options)](#apidoc.element.sugar.Date.daysFromNow)
- description and source-code
```javascript
daysFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.daysInMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>daysInMonth (date)](#apidoc.element.sugar.Date.daysInMonth)
- description and source-code
```javascript
daysInMonth = function (date) {
  return getDaysInMonth(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.daysSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>daysSince (date, d, options)](#apidoc.element.sugar.Date.daysSince)
- description and source-code
```javascript
daysSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.daysUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>daysUntil (date, d, options)](#apidoc.element.sugar.Date.daysUntil)
- description and source-code
```javascript
daysUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.endOfDay"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>endOfDay (d, localeCode)](#apidoc.element.sugar.Date.endOfDay)
- description and source-code
```javascript
endOfDay = function (d, localeCode) {
  return moveToEndOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.endOfISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>endOfISOWeek (date)](#apidoc.element.sugar.Date.endOfISOWeek)
- description and source-code
```javascript
endOfISOWeek = function (date) {
  if (getWeekday(date) !== 0) {
    setWeekday(date, 7);
  }
  return moveToEndOfUnit(date, DAY_INDEX);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.endOfMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>endOfMonth (d, localeCode)](#apidoc.element.sugar.Date.endOfMonth)
- description and source-code
```javascript
endOfMonth = function (d, localeCode) {
  return moveToEndOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.endOfWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>endOfWeek (d, localeCode)](#apidoc.element.sugar.Date.endOfWeek)
- description and source-code
```javascript
endOfWeek = function (d, localeCode) {
  return moveToEndOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.endOfYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>endOfYear (d, localeCode)](#apidoc.element.sugar.Date.endOfYear)
- description and source-code
```javascript
endOfYear = function (d, localeCode) {
  return moveToEndOfUnit(d, index, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.format"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>format (date, f, localeCode)](#apidoc.element.sugar.Date.format)
- description and source-code
```javascript
format = function (date, f, localeCode) {
  return dateFormat(date, f, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.full"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>full (d, localeCode)](#apidoc.element.sugar.Date.full)
- description and source-code
```javascript
full = function (d, localeCode) {
  var loc = localeManager.get(localeCode);
  return dateFormatMatcher(loc[name], d, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.get"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>get (date, d, options)](#apidoc.element.sugar.Date.get)
- description and source-code
```javascript
get = function (date, d, options) {
  return createDateWithContext(date, d, options);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Date.getAllLocaleCodes"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getAllLocaleCodes ()](#apidoc.element.sugar.Date.getAllLocaleCodes)
- description and source-code
```javascript
getAllLocaleCodes = function () {
  return getKeys(localeManager.getAll());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.getAllLocales"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getAllLocales ()](#apidoc.element.sugar.Date.getAllLocales)
- description and source-code
```javascript
getAllLocales = function () {
  return localeManager.getAll();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.getISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getISOWeek (date)](#apidoc.element.sugar.Date.getISOWeek)
- description and source-code
```javascript
getISOWeek = function (date) {
  return getWeekNumber(date, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.getLocale"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getLocale (code)](#apidoc.element.sugar.Date.getLocale)
- description and source-code
```javascript
getLocale = function (code) {
  return localeManager.get(code, !code);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.getUTCOffset"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getUTCOffset (date, iso)](#apidoc.element.sugar.Date.getUTCOffset)
- description and source-code
```javascript
getUTCOffset = function (date, iso) {
  return getUTCOffset(date, iso);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.getUTCWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getUTCWeekday (date)](#apidoc.element.sugar.Date.getUTCWeekday)
- description and source-code
```javascript
getUTCWeekday = function (date) {
  return date.getUTCDay();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.getWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>getWeekday (date)](#apidoc.element.sugar.Date.getWeekday)
- description and source-code
```javascript
getWeekday = function (date) {
  return getWeekday(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.hoursAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>hoursAgo (date, d, options)](#apidoc.element.sugar.Date.hoursAgo)
- description and source-code
```javascript
hoursAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.hoursFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>hoursFromNow (date, d, options)](#apidoc.element.sugar.Date.hoursFromNow)
- description and source-code
```javascript
hoursFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.hoursSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>hoursSince (date, d, options)](#apidoc.element.sugar.Date.hoursSince)
- description and source-code
```javascript
hoursSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.hoursUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>hoursUntil (date, d, options)](#apidoc.element.sugar.Date.hoursUntil)
- description and source-code
```javascript
hoursUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.is"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>is (date, d, margin)](#apidoc.element.sugar.Date.is)
- description and source-code
```javascript
is = function (date, d, margin) {
  return fullCompareDate(date, d, margin);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isAfter"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isAfter (date, d, margin)](#apidoc.element.sugar.Date.isAfter)
- description and source-code
```javascript
isAfter = function (date, d, margin) {
  return date.getTime() > createDate(d).getTime() - (margin || 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isApril"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isApril (d)](#apidoc.element.sugar.Date.isApril)
- description and source-code
```javascript
isApril = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isAugust"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isAugust (d)](#apidoc.element.sugar.Date.isAugust)
- description and source-code
```javascript
isAugust = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isBefore"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isBefore (date, d, margin)](#apidoc.element.sugar.Date.isBefore)
- description and source-code
```javascript
isBefore = function (date, d, margin) {
  return date.getTime() < createDate(d).getTime() + (margin || 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isBetween"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isBetween (date, d1, d2, margin)](#apidoc.element.sugar.Date.isBetween)
- description and source-code
```javascript
isBetween = function (date, d1, d2, margin) {
  var t  = date.getTime();
  var t1 = createDate(d1).getTime();
  var t2 = createDate(d2).getTime();
  var lo = min(t1, t2);
  var hi = max(t1, t2);
  margin = margin || 0;
  return (lo - margin <= t) && (hi + margin >= t);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isDecember"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isDecember (d)](#apidoc.element.sugar.Date.isDecember)
- description and source-code
```javascript
isDecember = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isFebruary"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isFebruary (d)](#apidoc.element.sugar.Date.isFebruary)
- description and source-code
```javascript
isFebruary = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isFriday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isFriday (d)](#apidoc.element.sugar.Date.isFriday)
- description and source-code
```javascript
isFriday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isFuture"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isFuture (d)](#apidoc.element.sugar.Date.isFuture)
- description and source-code
```javascript
isFuture = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isJanuary"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isJanuary (d)](#apidoc.element.sugar.Date.isJanuary)
- description and source-code
```javascript
isJanuary = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isJuly"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isJuly (d)](#apidoc.element.sugar.Date.isJuly)
- description and source-code
```javascript
isJuly = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isJune"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isJune (d)](#apidoc.element.sugar.Date.isJune)
- description and source-code
```javascript
isJune = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isLastMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isLastMonth (d, localeCode)](#apidoc.element.sugar.Date.isLastMonth)
- description and source-code
```javascript
isLastMonth = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isLastWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isLastWeek (d, localeCode)](#apidoc.element.sugar.Date.isLastWeek)
- description and source-code
```javascript
isLastWeek = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isLastYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isLastYear (d, localeCode)](#apidoc.element.sugar.Date.isLastYear)
- description and source-code
```javascript
isLastYear = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isLeapYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isLeapYear (date)](#apidoc.element.sugar.Date.isLeapYear)
- description and source-code
```javascript
isLeapYear = function (date) {
  var year = getYear(date);
  return (year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isMarch"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isMarch (d)](#apidoc.element.sugar.Date.isMarch)
- description and source-code
```javascript
isMarch = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isMay"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isMay (d)](#apidoc.element.sugar.Date.isMay)
- description and source-code
```javascript
isMay = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isMonday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isMonday (d)](#apidoc.element.sugar.Date.isMonday)
- description and source-code
```javascript
isMonday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isNextMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isNextMonth (d, localeCode)](#apidoc.element.sugar.Date.isNextMonth)
- description and source-code
```javascript
isNextMonth = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isNextWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isNextWeek (d, localeCode)](#apidoc.element.sugar.Date.isNextWeek)
- description and source-code
```javascript
isNextWeek = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isNextYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isNextYear (d, localeCode)](#apidoc.element.sugar.Date.isNextYear)
- description and source-code
```javascript
isNextYear = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isNovember"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isNovember (d)](#apidoc.element.sugar.Date.isNovember)
- description and source-code
```javascript
isNovember = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isOctober"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isOctober (d)](#apidoc.element.sugar.Date.isOctober)
- description and source-code
```javascript
isOctober = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isPast"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isPast (d)](#apidoc.element.sugar.Date.isPast)
- description and source-code
```javascript
isPast = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isSaturday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isSaturday (d)](#apidoc.element.sugar.Date.isSaturday)
- description and source-code
```javascript
isSaturday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isSeptember"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isSeptember (d)](#apidoc.element.sugar.Date.isSeptember)
- description and source-code
```javascript
isSeptember = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isSunday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isSunday (d)](#apidoc.element.sugar.Date.isSunday)
- description and source-code
```javascript
isSunday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isThisMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isThisMonth (d, localeCode)](#apidoc.element.sugar.Date.isThisMonth)
- description and source-code
```javascript
isThisMonth = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isThisWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isThisWeek (d, localeCode)](#apidoc.element.sugar.Date.isThisWeek)
- description and source-code
```javascript
isThisWeek = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isThisYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isThisYear (d, localeCode)](#apidoc.element.sugar.Date.isThisYear)
- description and source-code
```javascript
isThisYear = function (d, localeCode) {
  return compareDate(d, shift + ' ' + name, 0, localeCode, { locale: 'en' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isThursday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isThursday (d)](#apidoc.element.sugar.Date.isThursday)
- description and source-code
```javascript
isThursday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isToday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isToday (d)](#apidoc.element.sugar.Date.isToday)
- description and source-code
```javascript
isToday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isTomorrow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isTomorrow (d)](#apidoc.element.sugar.Date.isTomorrow)
- description and source-code
```javascript
isTomorrow = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isTuesday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isTuesday (d)](#apidoc.element.sugar.Date.isTuesday)
- description and source-code
```javascript
isTuesday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isUTC"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isUTC (date)](#apidoc.element.sugar.Date.isUTC)
- description and source-code
```javascript
isUTC = function (date) {
  return isUTC(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isValid"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isValid (date)](#apidoc.element.sugar.Date.isValid)
- description and source-code
```javascript
isValid = function (date) {
  return dateIsValid(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isWednesday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isWednesday (d)](#apidoc.element.sugar.Date.isWednesday)
- description and source-code
```javascript
isWednesday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isWeekday (d)](#apidoc.element.sugar.Date.isWeekday)
- description and source-code
```javascript
isWeekday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isWeekend"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isWeekend (d)](#apidoc.element.sugar.Date.isWeekend)
- description and source-code
```javascript
isWeekend = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.isYesterday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>isYesterday (d)](#apidoc.element.sugar.Date.isYesterday)
- description and source-code
```javascript
isYesterday = function (d) {
  return fullCompareDate(d, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.iso"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>iso (date)](#apidoc.element.sugar.Date.iso)
- description and source-code
```javascript
iso = function (date) {
  return date.toISOString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.long"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>long (d, localeCode)](#apidoc.element.sugar.Date.long)
- description and source-code
```javascript
long = function (d, localeCode) {
  var loc = localeManager.get(localeCode);
  return dateFormatMatcher(loc[name], d, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.medium"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>medium (d, localeCode)](#apidoc.element.sugar.Date.medium)
- description and source-code
```javascript
medium = function (d, localeCode) {
  var loc = localeManager.get(localeCode);
  return dateFormatMatcher(loc[name], d, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.millisecondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsAgo (date, d, options)](#apidoc.element.sugar.Date.millisecondsAgo)
- description and source-code
```javascript
millisecondsAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.millisecondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsFromNow (date, d, options)](#apidoc.element.sugar.Date.millisecondsFromNow)
- description and source-code
```javascript
millisecondsFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.millisecondsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsSince (date, d, options)](#apidoc.element.sugar.Date.millisecondsSince)
- description and source-code
```javascript
millisecondsSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.millisecondsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>millisecondsUntil (date, d, options)](#apidoc.element.sugar.Date.millisecondsUntil)
- description and source-code
```javascript
millisecondsUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.minutesAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>minutesAgo (date, d, options)](#apidoc.element.sugar.Date.minutesAgo)
- description and source-code
```javascript
minutesAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.minutesFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>minutesFromNow (date, d, options)](#apidoc.element.sugar.Date.minutesFromNow)
- description and source-code
```javascript
minutesFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.minutesSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>minutesSince (date, d, options)](#apidoc.element.sugar.Date.minutesSince)
- description and source-code
```javascript
minutesSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.minutesUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>minutesUntil (date, d, options)](#apidoc.element.sugar.Date.minutesUntil)
- description and source-code
```javascript
minutesUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.monthsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>monthsAgo (date, d, options)](#apidoc.element.sugar.Date.monthsAgo)
- description and source-code
```javascript
monthsAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.monthsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>monthsFromNow (date, d, options)](#apidoc.element.sugar.Date.monthsFromNow)
- description and source-code
```javascript
monthsFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.monthsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>monthsSince (date, d, options)](#apidoc.element.sugar.Date.monthsSince)
- description and source-code
```javascript
monthsSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.monthsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>monthsUntil (date, d, options)](#apidoc.element.sugar.Date.monthsUntil)
- description and source-code
```javascript
monthsUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.range"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>range (start, end)](#apidoc.element.sugar.Date.range)
- description and source-code
```javascript
range = function (start, end) {
  if (arguments.length === 1 && isString(start)) {
    return createDateRangeFromString(start);
  }
  return new Range(getDateForRange(start), getDateForRange(end));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.relative"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>relative (date, localeCode, fn)](#apidoc.element.sugar.Date.relative)
- description and source-code
```javascript
relative = function (date, localeCode, fn) {
  return dateRelative(date, null, localeCode, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.relativeTo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>relativeTo (date, d, localeCode)](#apidoc.element.sugar.Date.relativeTo)
- description and source-code
```javascript
relativeTo = function (date, d, localeCode) {
  return dateRelative(date, createDate(d), localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.removeLocale"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>removeLocale (code)](#apidoc.element.sugar.Date.removeLocale)
- description and source-code
```javascript
removeLocale = function (code) {
  return localeManager.remove(code);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.reset"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>reset (date, unit, localeCode)](#apidoc.element.sugar.Date.reset)
- description and source-code
```javascript
reset = function (date, unit, localeCode) {
  var unitIndex = unit ? getUnitIndexForParamName(unit) : DAY_INDEX;
  moveToBeginningOfUnit(date, unitIndex, localeCode);
  return date;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.rewind"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>rewind ()](#apidoc.element.sugar.Date.rewind)
- description and source-code
```javascript
rewind = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.secondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>secondsAgo (date, d, options)](#apidoc.element.sugar.Date.secondsAgo)
- description and source-code
```javascript
secondsAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.secondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>secondsFromNow (date, d, options)](#apidoc.element.sugar.Date.secondsFromNow)
- description and source-code
```javascript
secondsFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.secondsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>secondsSince (date, d, options)](#apidoc.element.sugar.Date.secondsSince)
- description and source-code
```javascript
secondsSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.secondsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>secondsUntil (date, d, options)](#apidoc.element.sugar.Date.secondsUntil)
- description and source-code
```javascript
secondsUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.set"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>set ()](#apidoc.element.sugar.Date.set)
- description and source-code
```javascript
set = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Date.setISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>setISOWeek (date, num)](#apidoc.element.sugar.Date.setISOWeek)
- description and source-code
```javascript
setISOWeek = function (date, num) {
  return setISOWeekNumber(date, num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.setLocale"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>setLocale (code)](#apidoc.element.sugar.Date.setLocale)
- description and source-code
```javascript
setLocale = function (code) {
  return localeManager.set(code);
}
```
- example usage
```shell
...
var addLocale = require('../date/addLocale');

/*
 * Catalan locale definition.
 * See the readme for customization and more information.
 * To set this locale globally:
 *
 * Sugar.Date.setLocale('ca')
 *
 */
addLocale('ca', {
'plural': true,
'units': 'milisegon:|s,segon:|s,minut:|s,hor:a|es,di:a|es,setman:a|es,mes:|os,any:|s',
'months': 'gen:er|,febr:er|,mar:ç|,abr:il|,mai:g|,jun:y|,jul:iol|,ag:ost|,set:embre|,oct:ubre|,nov:embre|,des:embre|',
'weekdays': 'diumenge|dg,dilluns|dl,dimarts|dt,dimecres|dc,dijous|dj,divendres|dv,dissabte|ds',
...
```

#### <a name="apidoc.element.sugar.Date.setUTC"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>setUTC (date, on)](#apidoc.element.sugar.Date.setUTC)
- description and source-code
```javascript
setUTC = function (date, on) {
  return _utc(date, on);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.setWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>setWeekday (date, dow)](#apidoc.element.sugar.Date.setWeekday)
- description and source-code
```javascript
setWeekday = function (date, dow) {
  return setWeekday(date, dow);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.short"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>short (d, localeCode)](#apidoc.element.sugar.Date.short)
- description and source-code
```javascript
short = function (d, localeCode) {
  var loc = localeManager.get(localeCode);
  return dateFormatMatcher(loc[name], d, localeCode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.weeksAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>weeksAgo (date, d, options)](#apidoc.element.sugar.Date.weeksAgo)
- description and source-code
```javascript
weeksAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.weeksFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>weeksFromNow (date, d, options)](#apidoc.element.sugar.Date.weeksFromNow)
- description and source-code
```javascript
weeksFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.weeksSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>weeksSince (date, d, options)](#apidoc.element.sugar.Date.weeksSince)
- description and source-code
```javascript
weeksSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.weeksUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>weeksUntil (date, d, options)](#apidoc.element.sugar.Date.weeksUntil)
- description and source-code
```javascript
weeksUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.yearsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>yearsAgo (date, d, options)](#apidoc.element.sugar.Date.yearsAgo)
- description and source-code
```javascript
yearsAgo = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.yearsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>yearsFromNow (date, d, options)](#apidoc.element.sugar.Date.yearsFromNow)
- description and source-code
```javascript
yearsFromNow = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.yearsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>yearsSince (date, d, options)](#apidoc.element.sugar.Date.yearsSince)
- description and source-code
```javascript
yearsSince = function (date, d, options) {
  return getTimeDistanceForUnit(date, createDateWithContext(date, d, options, true), unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.yearsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.</span>yearsUntil (date, d, options)](#apidoc.element.sugar.Date.yearsUntil)
- description and source-code
```javascript
yearsUntil = function (date, d, options) {
  return getTimeDistanceForUnit(createDateWithContext(date, d, options, true), date, unit);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Date.prototype"></a>[module sugar.Date.prototype](#apidoc.module.sugar.Date.prototype)

#### <a name="apidoc.element.sugar.Date.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Date.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Date.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Date.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Date.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>add ()](#apidoc.element.sugar.Date.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addAll ()](#apidoc.element.sugar.Date.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addDays"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addDays ()](#apidoc.element.sugar.Date.prototype.addDays)
- description and source-code
```javascript
addDays = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addHours"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addHours ()](#apidoc.element.sugar.Date.prototype.addHours)
- description and source-code
```javascript
addHours = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addMilliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addMilliseconds ()](#apidoc.element.sugar.Date.prototype.addMilliseconds)
- description and source-code
```javascript
addMilliseconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addMinutes"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addMinutes ()](#apidoc.element.sugar.Date.prototype.addMinutes)
- description and source-code
```javascript
addMinutes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addMonths"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addMonths ()](#apidoc.element.sugar.Date.prototype.addMonths)
- description and source-code
```javascript
addMonths = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addSeconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addSeconds ()](#apidoc.element.sugar.Date.prototype.addSeconds)
- description and source-code
```javascript
addSeconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addWeeks"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addWeeks ()](#apidoc.element.sugar.Date.prototype.addWeeks)
- description and source-code
```javascript
addWeeks = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.addYears"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>addYears ()](#apidoc.element.sugar.Date.prototype.addYears)
- description and source-code
```javascript
addYears = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.advance"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>advance ()](#apidoc.element.sugar.Date.prototype.advance)
- description and source-code
```javascript
advance = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>average ()](#apidoc.element.sugar.Date.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.beginningOfDay"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfDay ()](#apidoc.element.sugar.Date.prototype.beginningOfDay)
- description and source-code
```javascript
beginningOfDay = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.beginningOfISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfISOWeek ()](#apidoc.element.sugar.Date.prototype.beginningOfISOWeek)
- description and source-code
```javascript
beginningOfISOWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.beginningOfMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfMonth ()](#apidoc.element.sugar.Date.prototype.beginningOfMonth)
- description and source-code
```javascript
beginningOfMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.beginningOfWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfWeek ()](#apidoc.element.sugar.Date.prototype.beginningOfWeek)
- description and source-code
```javascript
beginningOfWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.beginningOfYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>beginningOfYear ()](#apidoc.element.sugar.Date.prototype.beginningOfYear)
- description and source-code
```javascript
beginningOfYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>clone ()](#apidoc.element.sugar.Date.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>count ()](#apidoc.element.sugar.Date.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.daysAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysAgo ()](#apidoc.element.sugar.Date.prototype.daysAgo)
- description and source-code
```javascript
daysAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.daysFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysFromNow ()](#apidoc.element.sugar.Date.prototype.daysFromNow)
- description and source-code
```javascript
daysFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.daysInMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysInMonth ()](#apidoc.element.sugar.Date.prototype.daysInMonth)
- description and source-code
```javascript
daysInMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.daysSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysSince ()](#apidoc.element.sugar.Date.prototype.daysSince)
- description and source-code
```javascript
daysSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.daysUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>daysUntil ()](#apidoc.element.sugar.Date.prototype.daysUntil)
- description and source-code
```javascript
daysUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>defaults ()](#apidoc.element.sugar.Date.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.endOfDay"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfDay ()](#apidoc.element.sugar.Date.prototype.endOfDay)
- description and source-code
```javascript
endOfDay = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.endOfISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfISOWeek ()](#apidoc.element.sugar.Date.prototype.endOfISOWeek)
- description and source-code
```javascript
endOfISOWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.endOfMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfMonth ()](#apidoc.element.sugar.Date.prototype.endOfMonth)
- description and source-code
```javascript
endOfMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.endOfWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfWeek ()](#apidoc.element.sugar.Date.prototype.endOfWeek)
- description and source-code
```javascript
endOfWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.endOfYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>endOfYear ()](#apidoc.element.sugar.Date.prototype.endOfYear)
- description and source-code
```javascript
endOfYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>every ()](#apidoc.element.sugar.Date.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>exclude ()](#apidoc.element.sugar.Date.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>filter ()](#apidoc.element.sugar.Date.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>find ()](#apidoc.element.sugar.Date.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>forEach ()](#apidoc.element.sugar.Date.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.format"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>format ()](#apidoc.element.sugar.Date.prototype.format)
- description and source-code
```javascript
format = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.full"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>full ()](#apidoc.element.sugar.Date.prototype.full)
- description and source-code
```javascript
full = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>get ()](#apidoc.element.sugar.Date.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.getDate"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getDate ()](#apidoc.element.sugar.Date.prototype.getDate)
- description and source-code
```javascript
getDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getDay"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getDay ()](#apidoc.element.sugar.Date.prototype.getDay)
- description and source-code
```javascript
getDay = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getFullYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getFullYear ()](#apidoc.element.sugar.Date.prototype.getFullYear)
- description and source-code
```javascript
getFullYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getHours"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getHours ()](#apidoc.element.sugar.Date.prototype.getHours)
- description and source-code
```javascript
getHours = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getISOWeek ()](#apidoc.element.sugar.Date.prototype.getISOWeek)
- description and source-code
```javascript
getISOWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getMilliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getMilliseconds ()](#apidoc.element.sugar.Date.prototype.getMilliseconds)
- description and source-code
```javascript
getMilliseconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getMinutes"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getMinutes ()](#apidoc.element.sugar.Date.prototype.getMinutes)
- description and source-code
```javascript
getMinutes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getMonth ()](#apidoc.element.sugar.Date.prototype.getMonth)
- description and source-code
```javascript
getMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getSeconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getSeconds ()](#apidoc.element.sugar.Date.prototype.getSeconds)
- description and source-code
```javascript
getSeconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getTime"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getTime ()](#apidoc.element.sugar.Date.prototype.getTime)
- description and source-code
```javascript
getTime = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...

var Sugar = require('sugar-core'),
    createDate = require('./internal/createDate');

Sugar.Date.defineInstance({

  'isAfter': function(date, d, margin) {
    return date.getTime() > createDate(d).getTime() - (margin || 0);
  }

});

module.exports = Sugar.Date.isAfter;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.getTimezoneOffset"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getTimezoneOffset ()](#apidoc.element.sugar.Date.prototype.getTimezoneOffset)
- description and source-code
```javascript
getTimezoneOffset = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCDate"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCDate ()](#apidoc.element.sugar.Date.prototype.getUTCDate)
- description and source-code
```javascript
getUTCDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCDay"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCDay ()](#apidoc.element.sugar.Date.prototype.getUTCDay)
- description and source-code
```javascript
getUTCDay = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
'use strict';

var Sugar = require('sugar-core');

Sugar.Date.defineInstance({

  'getUTCWeekday': function(date) {
    return date.getUTCDay();
  }

});

module.exports = Sugar.Date.getUTCWeekday;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCFullYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCFullYear ()](#apidoc.element.sugar.Date.prototype.getUTCFullYear)
- description and source-code
```javascript
getUTCFullYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCHours"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCHours ()](#apidoc.element.sugar.Date.prototype.getUTCHours)
- description and source-code
```javascript
getUTCHours = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCMilliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCMilliseconds ()](#apidoc.element.sugar.Date.prototype.getUTCMilliseconds)
- description and source-code
```javascript
getUTCMilliseconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCMinutes"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCMinutes ()](#apidoc.element.sugar.Date.prototype.getUTCMinutes)
- description and source-code
```javascript
getUTCMinutes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCMonth ()](#apidoc.element.sugar.Date.prototype.getUTCMonth)
- description and source-code
```javascript
getUTCMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCOffset"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCOffset ()](#apidoc.element.sugar.Date.prototype.getUTCOffset)
- description and source-code
```javascript
getUTCOffset = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCSeconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCSeconds ()](#apidoc.element.sugar.Date.prototype.getUTCSeconds)
- description and source-code
```javascript
getUTCSeconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getUTCWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getUTCWeekday ()](#apidoc.element.sugar.Date.prototype.getUTCWeekday)
- description and source-code
```javascript
getUTCWeekday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getWeekday ()](#apidoc.element.sugar.Date.prototype.getWeekday)
- description and source-code
```javascript
getWeekday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.getYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>getYear ()](#apidoc.element.sugar.Date.prototype.getYear)
- description and source-code
```javascript
getYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>has ()](#apidoc.element.sugar.Date.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Date.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.hoursAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursAgo ()](#apidoc.element.sugar.Date.prototype.hoursAgo)
- description and source-code
```javascript
hoursAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.hoursFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursFromNow ()](#apidoc.element.sugar.Date.prototype.hoursFromNow)
- description and source-code
```javascript
hoursFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.hoursSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursSince ()](#apidoc.element.sugar.Date.prototype.hoursSince)
- description and source-code
```javascript
hoursSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.hoursUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>hoursUntil ()](#apidoc.element.sugar.Date.prototype.hoursUntil)
- description and source-code
```javascript
hoursUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>intersect ()](#apidoc.element.sugar.Date.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>invert ()](#apidoc.element.sugar.Date.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.is"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>is ()](#apidoc.element.sugar.Date.prototype.is)
- description and source-code
```javascript
is = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isAfter"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isAfter ()](#apidoc.element.sugar.Date.prototype.isAfter)
- description and source-code
```javascript
isAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isApril"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isApril ()](#apidoc.element.sugar.Date.prototype.isApril)
- description and source-code
```javascript
isApril = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isArguments ()](#apidoc.element.sugar.Date.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isArray ()](#apidoc.element.sugar.Date.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isAugust"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isAugust ()](#apidoc.element.sugar.Date.prototype.isAugust)
- description and source-code
```javascript
isAugust = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isBefore"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isBefore ()](#apidoc.element.sugar.Date.prototype.isBefore)
- description and source-code
```javascript
isBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isBetween"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isBetween ()](#apidoc.element.sugar.Date.prototype.isBetween)
- description and source-code
```javascript
isBetween = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isBoolean ()](#apidoc.element.sugar.Date.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isDate ()](#apidoc.element.sugar.Date.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isDecember"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isDecember ()](#apidoc.element.sugar.Date.prototype.isDecember)
- description and source-code
```javascript
isDecember = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isEmpty ()](#apidoc.element.sugar.Date.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isEqual ()](#apidoc.element.sugar.Date.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isError ()](#apidoc.element.sugar.Date.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isFebruary"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFebruary ()](#apidoc.element.sugar.Date.prototype.isFebruary)
- description and source-code
```javascript
isFebruary = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isFriday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFriday ()](#apidoc.element.sugar.Date.prototype.isFriday)
- description and source-code
```javascript
isFriday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFunction ()](#apidoc.element.sugar.Date.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isFuture"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isFuture ()](#apidoc.element.sugar.Date.prototype.isFuture)
- description and source-code
```javascript
isFuture = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isJanuary"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isJanuary ()](#apidoc.element.sugar.Date.prototype.isJanuary)
- description and source-code
```javascript
isJanuary = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isJuly"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isJuly ()](#apidoc.element.sugar.Date.prototype.isJuly)
- description and source-code
```javascript
isJuly = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isJune"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isJune ()](#apidoc.element.sugar.Date.prototype.isJune)
- description and source-code
```javascript
isJune = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isLastMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLastMonth ()](#apidoc.element.sugar.Date.prototype.isLastMonth)
- description and source-code
```javascript
isLastMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isLastWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLastWeek ()](#apidoc.element.sugar.Date.prototype.isLastWeek)
- description and source-code
```javascript
isLastWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isLastYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLastYear ()](#apidoc.element.sugar.Date.prototype.isLastYear)
- description and source-code
```javascript
isLastYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isLeapYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isLeapYear ()](#apidoc.element.sugar.Date.prototype.isLeapYear)
- description and source-code
```javascript
isLeapYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMap ()](#apidoc.element.sugar.Date.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isMarch"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMarch ()](#apidoc.element.sugar.Date.prototype.isMarch)
- description and source-code
```javascript
isMarch = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isMay"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMay ()](#apidoc.element.sugar.Date.prototype.isMay)
- description and source-code
```javascript
isMay = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isMonday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isMonday ()](#apidoc.element.sugar.Date.prototype.isMonday)
- description and source-code
```javascript
isMonday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isNextMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNextMonth ()](#apidoc.element.sugar.Date.prototype.isNextMonth)
- description and source-code
```javascript
isNextMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isNextWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNextWeek ()](#apidoc.element.sugar.Date.prototype.isNextWeek)
- description and source-code
```javascript
isNextWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isNextYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNextYear ()](#apidoc.element.sugar.Date.prototype.isNextYear)
- description and source-code
```javascript
isNextYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isNovember"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNovember ()](#apidoc.element.sugar.Date.prototype.isNovember)
- description and source-code
```javascript
isNovember = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isNumber ()](#apidoc.element.sugar.Date.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isObject ()](#apidoc.element.sugar.Date.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isOctober"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isOctober ()](#apidoc.element.sugar.Date.prototype.isOctober)
- description and source-code
```javascript
isOctober = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isPast"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isPast ()](#apidoc.element.sugar.Date.prototype.isPast)
- description and source-code
```javascript
isPast = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Date.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isRegExp ()](#apidoc.element.sugar.Date.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isSaturday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSaturday ()](#apidoc.element.sugar.Date.prototype.isSaturday)
- description and source-code
```javascript
isSaturday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isSeptember"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSeptember ()](#apidoc.element.sugar.Date.prototype.isSeptember)
- description and source-code
```javascript
isSeptember = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSet ()](#apidoc.element.sugar.Date.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isString ()](#apidoc.element.sugar.Date.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isSunday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isSunday ()](#apidoc.element.sugar.Date.prototype.isSunday)
- description and source-code
```javascript
isSunday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isThisMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThisMonth ()](#apidoc.element.sugar.Date.prototype.isThisMonth)
- description and source-code
```javascript
isThisMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isThisWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThisWeek ()](#apidoc.element.sugar.Date.prototype.isThisWeek)
- description and source-code
```javascript
isThisWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isThisYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThisYear ()](#apidoc.element.sugar.Date.prototype.isThisYear)
- description and source-code
```javascript
isThisYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isThursday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isThursday ()](#apidoc.element.sugar.Date.prototype.isThursday)
- description and source-code
```javascript
isThursday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isToday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isToday ()](#apidoc.element.sugar.Date.prototype.isToday)
- description and source-code
```javascript
isToday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isTomorrow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isTomorrow ()](#apidoc.element.sugar.Date.prototype.isTomorrow)
- description and source-code
```javascript
isTomorrow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isTuesday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isTuesday ()](#apidoc.element.sugar.Date.prototype.isTuesday)
- description and source-code
```javascript
isTuesday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isUTC"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isUTC ()](#apidoc.element.sugar.Date.prototype.isUTC)
- description and source-code
```javascript
isUTC = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isValid"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isValid ()](#apidoc.element.sugar.Date.prototype.isValid)
- description and source-code
```javascript
isValid = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isWednesday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isWednesday ()](#apidoc.element.sugar.Date.prototype.isWednesday)
- description and source-code
```javascript
isWednesday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isWeekday ()](#apidoc.element.sugar.Date.prototype.isWeekday)
- description and source-code
```javascript
isWeekday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isWeekend"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isWeekend ()](#apidoc.element.sugar.Date.prototype.isWeekend)
- description and source-code
```javascript
isWeekend = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.isYesterday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>isYesterday ()](#apidoc.element.sugar.Date.prototype.isYesterday)
- description and source-code
```javascript
isYesterday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.iso"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>iso ()](#apidoc.element.sugar.Date.prototype.iso)
- description and source-code
```javascript
iso = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>keys ()](#apidoc.element.sugar.Date.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>least ()](#apidoc.element.sugar.Date.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.long"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>long ()](#apidoc.element.sugar.Date.prototype.long)
- description and source-code
```javascript
long = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>map ()](#apidoc.element.sugar.Date.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>max ()](#apidoc.element.sugar.Date.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>median ()](#apidoc.element.sugar.Date.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.medium"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>medium ()](#apidoc.element.sugar.Date.prototype.medium)
- description and source-code
```javascript
medium = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>merge ()](#apidoc.element.sugar.Date.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>mergeAll ()](#apidoc.element.sugar.Date.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.millisecondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsAgo ()](#apidoc.element.sugar.Date.prototype.millisecondsAgo)
- description and source-code
```javascript
millisecondsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.millisecondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsFromNow ()](#apidoc.element.sugar.Date.prototype.millisecondsFromNow)
- description and source-code
```javascript
millisecondsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.millisecondsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsSince ()](#apidoc.element.sugar.Date.prototype.millisecondsSince)
- description and source-code
```javascript
millisecondsSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.millisecondsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>millisecondsUntil ()](#apidoc.element.sugar.Date.prototype.millisecondsUntil)
- description and source-code
```javascript
millisecondsUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>min ()](#apidoc.element.sugar.Date.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.minutesAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesAgo ()](#apidoc.element.sugar.Date.prototype.minutesAgo)
- description and source-code
```javascript
minutesAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.minutesFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesFromNow ()](#apidoc.element.sugar.Date.prototype.minutesFromNow)
- description and source-code
```javascript
minutesFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.minutesSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesSince ()](#apidoc.element.sugar.Date.prototype.minutesSince)
- description and source-code
```javascript
minutesSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.minutesUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>minutesUntil ()](#apidoc.element.sugar.Date.prototype.minutesUntil)
- description and source-code
```javascript
minutesUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.monthsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsAgo ()](#apidoc.element.sugar.Date.prototype.monthsAgo)
- description and source-code
```javascript
monthsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.monthsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsFromNow ()](#apidoc.element.sugar.Date.prototype.monthsFromNow)
- description and source-code
```javascript
monthsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.monthsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsSince ()](#apidoc.element.sugar.Date.prototype.monthsSince)
- description and source-code
```javascript
monthsSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.monthsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>monthsUntil ()](#apidoc.element.sugar.Date.prototype.monthsUntil)
- description and source-code
```javascript
monthsUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>most ()](#apidoc.element.sugar.Date.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>none ()](#apidoc.element.sugar.Date.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Date.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>reduce ()](#apidoc.element.sugar.Date.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>reject ()](#apidoc.element.sugar.Date.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.relative"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>relative ()](#apidoc.element.sugar.Date.prototype.relative)
- description and source-code
```javascript
relative = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.relativeTo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>relativeTo ()](#apidoc.element.sugar.Date.prototype.relativeTo)
- description and source-code
```javascript
relativeTo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>remove ()](#apidoc.element.sugar.Date.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.reset"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>reset ()](#apidoc.element.sugar.Date.prototype.reset)
- description and source-code
```javascript
reset = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.rewind"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>rewind ()](#apidoc.element.sugar.Date.prototype.rewind)
- description and source-code
```javascript
rewind = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.secondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsAgo ()](#apidoc.element.sugar.Date.prototype.secondsAgo)
- description and source-code
```javascript
secondsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.secondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsFromNow ()](#apidoc.element.sugar.Date.prototype.secondsFromNow)
- description and source-code
```javascript
secondsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.secondsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsSince ()](#apidoc.element.sugar.Date.prototype.secondsSince)
- description and source-code
```javascript
secondsSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.secondsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>secondsUntil ()](#apidoc.element.sugar.Date.prototype.secondsUntil)
- description and source-code
```javascript
secondsUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>select ()](#apidoc.element.sugar.Date.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>set ()](#apidoc.element.sugar.Date.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.setDate"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setDate ()](#apidoc.element.sugar.Date.prototype.setDate)
- description and source-code
```javascript
setDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setFullYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setFullYear ()](#apidoc.element.sugar.Date.prototype.setFullYear)
- description and source-code
```javascript
setFullYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setHours"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setHours ()](#apidoc.element.sugar.Date.prototype.setHours)
- description and source-code
```javascript
setHours = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setISOWeek"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setISOWeek ()](#apidoc.element.sugar.Date.prototype.setISOWeek)
- description and source-code
```javascript
setISOWeek = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setMilliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setMilliseconds ()](#apidoc.element.sugar.Date.prototype.setMilliseconds)
- description and source-code
```javascript
setMilliseconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setMinutes"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setMinutes ()](#apidoc.element.sugar.Date.prototype.setMinutes)
- description and source-code
```javascript
setMinutes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setMonth ()](#apidoc.element.sugar.Date.prototype.setMonth)
- description and source-code
```javascript
setMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setSeconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setSeconds ()](#apidoc.element.sugar.Date.prototype.setSeconds)
- description and source-code
```javascript
setSeconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setTime"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setTime ()](#apidoc.element.sugar.Date.prototype.setTime)
- description and source-code
```javascript
setTime = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTC"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTC ()](#apidoc.element.sugar.Date.prototype.setUTC)
- description and source-code
```javascript
setUTC = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCDate"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCDate ()](#apidoc.element.sugar.Date.prototype.setUTCDate)
- description and source-code
```javascript
setUTCDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCFullYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCFullYear ()](#apidoc.element.sugar.Date.prototype.setUTCFullYear)
- description and source-code
```javascript
setUTCFullYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCHours"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCHours ()](#apidoc.element.sugar.Date.prototype.setUTCHours)
- description and source-code
```javascript
setUTCHours = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCMilliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCMilliseconds ()](#apidoc.element.sugar.Date.prototype.setUTCMilliseconds)
- description and source-code
```javascript
setUTCMilliseconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCMinutes"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCMinutes ()](#apidoc.element.sugar.Date.prototype.setUTCMinutes)
- description and source-code
```javascript
setUTCMinutes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCMonth"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCMonth ()](#apidoc.element.sugar.Date.prototype.setUTCMonth)
- description and source-code
```javascript
setUTCMonth = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setUTCSeconds"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setUTCSeconds ()](#apidoc.element.sugar.Date.prototype.setUTCSeconds)
- description and source-code
```javascript
setUTCSeconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setWeekday"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setWeekday ()](#apidoc.element.sugar.Date.prototype.setWeekday)
- description and source-code
```javascript
setWeekday = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.setYear"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>setYear ()](#apidoc.element.sugar.Date.prototype.setYear)
- description and source-code
```javascript
setYear = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.short"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>short ()](#apidoc.element.sugar.Date.prototype.short)
- description and source-code
```javascript
short = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>size ()](#apidoc.element.sugar.Date.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>some ()](#apidoc.element.sugar.Date.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>subtract ()](#apidoc.element.sugar.Date.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>sum ()](#apidoc.element.sugar.Date.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>tap ()](#apidoc.element.sugar.Date.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toDateString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toDateString ()](#apidoc.element.sugar.Date.prototype.toDateString)
- description and source-code
```javascript
toDateString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toGMTString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toGMTString ()](#apidoc.element.sugar.Date.prototype.toGMTString)
- description and source-code
```javascript
toGMTString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toISOString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toISOString ()](#apidoc.element.sugar.Date.prototype.toISOString)
- description and source-code
```javascript
toISOString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
'use strict';

var Sugar = require('sugar-core');

Sugar.Date.defineInstance({

  'iso': function(date) {
    return date.toISOString();
  }

});

module.exports = Sugar.Date.iso;
...
```

#### <a name="apidoc.element.sugar.Date.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toJSON ()](#apidoc.element.sugar.Date.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toLocaleDateString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toLocaleDateString ()](#apidoc.element.sugar.Date.prototype.toLocaleDateString)
- description and source-code
```javascript
toLocaleDateString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Date.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toLocaleTimeString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toLocaleTimeString ()](#apidoc.element.sugar.Date.prototype.toLocaleTimeString)
- description and source-code
```javascript
toLocaleTimeString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toQueryString ()](#apidoc.element.sugar.Date.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toString ()](#apidoc.element.sugar.Date.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.Date.prototype.toTimeString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toTimeString ()](#apidoc.element.sugar.Date.prototype.toTimeString)
- description and source-code
```javascript
toTimeString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.toUTCString"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>toUTCString ()](#apidoc.element.sugar.Date.prototype.toUTCString)
- description and source-code
```javascript
toUTCString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>values ()](#apidoc.element.sugar.Date.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.weeksAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksAgo ()](#apidoc.element.sugar.Date.prototype.weeksAgo)
- description and source-code
```javascript
weeksAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.weeksFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksFromNow ()](#apidoc.element.sugar.Date.prototype.weeksFromNow)
- description and source-code
```javascript
weeksFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.weeksSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksSince ()](#apidoc.element.sugar.Date.prototype.weeksSince)
- description and source-code
```javascript
weeksSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.weeksUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>weeksUntil ()](#apidoc.element.sugar.Date.prototype.weeksUntil)
- description and source-code
```javascript
weeksUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.yearsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsAgo ()](#apidoc.element.sugar.Date.prototype.yearsAgo)
- description and source-code
```javascript
yearsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.yearsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsFromNow ()](#apidoc.element.sugar.Date.prototype.yearsFromNow)
- description and source-code
```javascript
yearsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.yearsSince"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsSince ()](#apidoc.element.sugar.Date.prototype.yearsSince)
- description and source-code
```javascript
yearsSince = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Date.prototype.yearsUntil"></a>[function <span class="apidocSignatureSpan">sugar.Date.prototype.</span>yearsUntil ()](#apidoc.element.sugar.Date.prototype.yearsUntil)
- description and source-code
```javascript
yearsUntil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Function"></a>[module sugar.Function](#apidoc.module.sugar.Function)

#### <a name="apidoc.element.sugar.Function.Function"></a>[function <span class="apidocSignatureSpan">sugar.</span>Function {{signature}}](#apidoc.element.sugar.Function.Function)
- description and source-code
```javascript
SugarFunction
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.after"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>after (fn, num)](#apidoc.element.sugar.Function.after)
- description and source-code
```javascript
after = function (fn, num) {
  var count = 0, collectedArgs = [];
  num = coercePositiveInteger(num);
  return function() {
    // Optimized: no leaking arguments
    var args = []; for(var $i = 0, $len = arguments.length; $i < $len; $i++) args.push(arguments[$i]);
    collectedArgs.push(args);
    count++;
    if (count >= num) {
      return fn.call(this, collectedArgs);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.cancel"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>cancel (fn)](#apidoc.element.sugar.Function.cancel)
- description and source-code
```javascript
cancel = function (fn) {
  return cancelFunction(fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.debounce"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>debounce (fn, ms)](#apidoc.element.sugar.Function.debounce)
- description and source-code
```javascript
debounce = function (fn, ms) {
  function debounced() {
    // Optimized: no leaking arguments
    var args = []; for(var $i = 0, $len = arguments.length; $i < $len; $i++) args.push(arguments[$i]);
    cancelFunction(debounced);
    setDelay(debounced, ms, fn, this, args);
  }
  return debounced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.delay"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>delay ()](#apidoc.element.sugar.Function.delay)
- description and source-code
```javascript
delay = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.every"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>every ()](#apidoc.element.sugar.Function.every)
- description and source-code
```javascript
every = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.lazy"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>lazy (fn, ms, immediate, limit)](#apidoc.element.sugar.Function.lazy)
- description and source-code
```javascript
lazy = function (fn, ms, immediate, limit) {
  return createLazyFunction(fn, ms, immediate, limit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.lock"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>lock (fn, n)](#apidoc.element.sugar.Function.lock)
- description and source-code
```javascript
lock = function (fn, n) {
  var lockedFn;
  if (_partial(fn)) {
    _lock(fn, isNumber(n) ? n : null);
    return fn;
  }
  lockedFn = function() {
    arguments.length = min(_lock(lockedFn), arguments.length);
    return fn.apply(this, arguments);
  };
  _lock(lockedFn, isNumber(n) ? n : fn.length);
  return lockedFn;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.memoize"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>memoize (fn, arg1, arg2)](#apidoc.element.sugar.Function.memoize)
- description and source-code
```javascript
memoize = function (fn, arg1, arg2) {
  var hashFn, limit, prop;
  if (isNumber(arg1)) {
    limit = arg1;
  } else {
    hashFn = arg1;
    limit  = arg2;
  }
  if (isString(hashFn)) {
    prop = hashFn;
    hashFn = function(obj) {
      return deepGetProperty(obj, prop);
    };
  } else if (!hashFn) {
    hashFn = collectArguments;
  }
  return createHashedMemoizeFunction(fn, hashFn, limit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.once"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>once (fn)](#apidoc.element.sugar.Function.once)
- description and source-code
```javascript
once = function (fn) {
  var called = false, val;
  return function() {
    if (called) {
      return val;
    }
    called = true;
    return val = fn.apply(this, arguments);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.partial"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>partial ()](#apidoc.element.sugar.Function.partial)
- description and source-code
```javascript
partial = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.throttle"></a>[function <span class="apidocSignatureSpan">sugar.Function.</span>throttle (fn, ms)](#apidoc.element.sugar.Function.throttle)
- description and source-code
```javascript
throttle = function (fn, ms) {
  return createLazyFunction(fn, ms, true, 1);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Function.prototype"></a>[module sugar.Function.prototype](#apidoc.module.sugar.Function.prototype)

#### <a name="apidoc.element.sugar.Function.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Function.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Function.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Function.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Function.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>add ()](#apidoc.element.sugar.Function.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Function.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>addAll ()](#apidoc.element.sugar.Function.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.after"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>after ()](#apidoc.element.sugar.Function.prototype.after)
- description and source-code
```javascript
after = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.apply"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>apply ()](#apidoc.element.sugar.Function.prototype.apply)
- description and source-code
```javascript
apply = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
Sugar.Function.defineInstanceWithArguments({

  'every': function(fn, ms, args) {
    function execute () {
      // Set the delay first here, so that cancel
      // can be called within the executing function.
      setDelay(fn, ms, execute);
      fn.apply(fn, args);
    }
    setDelay(fn, ms, execute);
    return fn;
  }

});
...
```

#### <a name="apidoc.element.sugar.Function.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>average ()](#apidoc.element.sugar.Function.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.bind"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>bind ()](#apidoc.element.sugar.Function.prototype.bind)
- description and source-code
```javascript
bind = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.call"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>call ()](#apidoc.element.sugar.Function.prototype.call)
- description and source-code
```javascript
call = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    num = coercePositiveInteger(num);
    return function() {
      // Optimized: no leaking arguments
      var args = []; for(var $i = 0, $len = arguments.length; $i < $len; $i++) args.push(arguments[$i]);
      collectedArgs.push(args);
      count++;
      if (count >= num) {
        return fn.call(this, collectedArgs);
      }
    };
  }

});

module.exports = Sugar.Function.after;
...
```

#### <a name="apidoc.element.sugar.Function.prototype.cancel"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>cancel ()](#apidoc.element.sugar.Function.prototype.cancel)
- description and source-code
```javascript
cancel = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>clone ()](#apidoc.element.sugar.Function.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>count ()](#apidoc.element.sugar.Function.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.debounce"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>debounce ()](#apidoc.element.sugar.Function.prototype.debounce)
- description and source-code
```javascript
debounce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>defaults ()](#apidoc.element.sugar.Function.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.delay"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>delay ()](#apidoc.element.sugar.Function.prototype.delay)
- description and source-code
```javascript
delay = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>every ()](#apidoc.element.sugar.Function.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>exclude ()](#apidoc.element.sugar.Function.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>filter ()](#apidoc.element.sugar.Function.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>find ()](#apidoc.element.sugar.Function.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>forEach ()](#apidoc.element.sugar.Function.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>get ()](#apidoc.element.sugar.Function.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Function.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>has ()](#apidoc.element.sugar.Function.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Function.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>intersect ()](#apidoc.element.sugar.Function.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>invert ()](#apidoc.element.sugar.Function.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isArguments ()](#apidoc.element.sugar.Function.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isArray ()](#apidoc.element.sugar.Function.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isBoolean ()](#apidoc.element.sugar.Function.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isDate ()](#apidoc.element.sugar.Function.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isEmpty ()](#apidoc.element.sugar.Function.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isEqual ()](#apidoc.element.sugar.Function.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isError ()](#apidoc.element.sugar.Function.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isFunction ()](#apidoc.element.sugar.Function.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isMap ()](#apidoc.element.sugar.Function.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isNumber ()](#apidoc.element.sugar.Function.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isObject ()](#apidoc.element.sugar.Function.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Function.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isRegExp ()](#apidoc.element.sugar.Function.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isSet ()](#apidoc.element.sugar.Function.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>isString ()](#apidoc.element.sugar.Function.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>keys ()](#apidoc.element.sugar.Function.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.lazy"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>lazy ()](#apidoc.element.sugar.Function.prototype.lazy)
- description and source-code
```javascript
lazy = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>least ()](#apidoc.element.sugar.Function.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.lock"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>lock ()](#apidoc.element.sugar.Function.prototype.lock)
- description and source-code
```javascript
lock = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>map ()](#apidoc.element.sugar.Function.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>max ()](#apidoc.element.sugar.Function.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>median ()](#apidoc.element.sugar.Function.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.memoize"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>memoize ()](#apidoc.element.sugar.Function.prototype.memoize)
- description and source-code
```javascript
memoize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>merge ()](#apidoc.element.sugar.Function.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>mergeAll ()](#apidoc.element.sugar.Function.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>min ()](#apidoc.element.sugar.Function.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>most ()](#apidoc.element.sugar.Function.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>none ()](#apidoc.element.sugar.Function.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.once"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>once ()](#apidoc.element.sugar.Function.prototype.once)
- description and source-code
```javascript
once = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.partial"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>partial ()](#apidoc.element.sugar.Function.prototype.partial)
- description and source-code
```javascript
partial = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Function.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>reduce ()](#apidoc.element.sugar.Function.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>reject ()](#apidoc.element.sugar.Function.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>remove ()](#apidoc.element.sugar.Function.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Function.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>select ()](#apidoc.element.sugar.Function.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>set ()](#apidoc.element.sugar.Function.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Function.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>size ()](#apidoc.element.sugar.Function.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>some ()](#apidoc.element.sugar.Function.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>subtract ()](#apidoc.element.sugar.Function.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>sum ()](#apidoc.element.sugar.Function.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>tap ()](#apidoc.element.sugar.Function.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.throttle"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>throttle ()](#apidoc.element.sugar.Function.prototype.throttle)
- description and source-code
```javascript
throttle = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Function.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>toQueryString ()](#apidoc.element.sugar.Function.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Function.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>toString ()](#apidoc.element.sugar.Function.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.Function.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.Function.prototype.</span>values ()](#apidoc.element.sugar.Function.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Number"></a>[module sugar.Number](#apidoc.module.sugar.Number)

#### <a name="apidoc.element.sugar.Number.Number"></a>[function <span class="apidocSignatureSpan">sugar.</span>Number {{signature}}](#apidoc.element.sugar.Number.Number)
- description and source-code
```javascript
SugarNumber
```
- example usage
```shell
...
  },
  'cube': function (n) {
    return n * n * n;
  }
});

Sugar.Number.square(3);         // 9
new Sugar.Number(5).cube().raw; // 125
Sugar.Number.randomish()        // ???

Sugar.extend();
(2).square();       // 4
(4).cube();         // 64
Number.randomish(); // ???
...
```

#### <a name="apidoc.element.sugar.Number.abbr"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>abbr (n, precision)](#apidoc.element.sugar.Number.abbr)
- description and source-code
```javascript
abbr = function (n, precision) {
  return abbreviateNumber(n, precision, BASIC_UNITS);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.abs"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>abs (n, arg)](#apidoc.element.sugar.Number.abs)
- description and source-code
```javascript
abs = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.acos"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>acos (n, arg)](#apidoc.element.sugar.Number.acos)
- description and source-code
```javascript
acos = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.asin"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>asin (n, arg)](#apidoc.element.sugar.Number.asin)
- description and source-code
```javascript
asin = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.atan"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>atan (n, arg)](#apidoc.element.sugar.Number.atan)
- description and source-code
```javascript
atan = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.bytes"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>bytes (n, precision, binary, units)](#apidoc.element.sugar.Number.bytes)
- description and source-code
```javascript
bytes = function (n, precision, binary, units) {
  if (units === 'binary' || (!units && binary)) {
    units = MEMORY_BINARY_UNITS;
  } else if(units === 'si' || !units) {
    units = MEMORY_UNITS;
  }
  return abbreviateNumber(n, precision, units, binary) + 'B';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.cap"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>cap (n, max)](#apidoc.element.sugar.Number.cap)
- description and source-code
```javascript
cap = function (n, max) {
  return rangeClamp(new Range(undefined, max), n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.ceil"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>ceil (n, precision)](#apidoc.element.sugar.Number.ceil)
- description and source-code
```javascript
ceil = function (n, precision) {
  return precision ? withPrecision(n, precision, fn) : fn(n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.chr"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>chr (n)](#apidoc.element.sugar.Number.chr)
- description and source-code
```javascript
chr = function (n) {
  return chr(n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.clamp"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>clamp (n, start, end)](#apidoc.element.sugar.Number.clamp)
- description and source-code
```javascript
clamp = function (n, start, end) {
  return rangeClamp(new Range(start, end), n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.cos"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>cos (n, arg)](#apidoc.element.sugar.Number.cos)
- description and source-code
```javascript
cos = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.day"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>day (n)](#apidoc.element.sugar.Number.day)
- description and source-code
```javascript
day = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.dayAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>dayAfter (n, d, options)](#apidoc.element.sugar.Number.dayAfter)
- description and source-code
```javascript
dayAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.dayAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>dayAgo (n, d, options)](#apidoc.element.sugar.Number.dayAgo)
- description and source-code
```javascript
dayAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.dayBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>dayBefore (n, d, options)](#apidoc.element.sugar.Number.dayBefore)
- description and source-code
```javascript
dayBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.dayFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>dayFromNow (n, d, options)](#apidoc.element.sugar.Number.dayFromNow)
- description and source-code
```javascript
dayFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.days"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>days (n)](#apidoc.element.sugar.Number.days)
- description and source-code
```javascript
days = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.daysAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>daysAfter (n, d, options)](#apidoc.element.sugar.Number.daysAfter)
- description and source-code
```javascript
daysAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.daysAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>daysAgo (n, d, options)](#apidoc.element.sugar.Number.daysAgo)
- description and source-code
```javascript
daysAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.daysBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>daysBefore (n, d, options)](#apidoc.element.sugar.Number.daysBefore)
- description and source-code
```javascript
daysBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.daysFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>daysFromNow (n, d, options)](#apidoc.element.sugar.Number.daysFromNow)
- description and source-code
```javascript
daysFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.downto"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>downto (n, num, step, fn)](#apidoc.element.sugar.Number.downto)
- description and source-code
```javascript
downto = function (n, num, step, fn) {
  return rangeEvery(new Range(n, num), step, false, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.duration"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>duration (n, localeCode)](#apidoc.element.sugar.Number.duration)
- description and source-code
```javascript
duration = function (n, localeCode) {
  return localeManager.get(localeCode).getDuration(n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.exp"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>exp (n, arg)](#apidoc.element.sugar.Number.exp)
- description and source-code
```javascript
exp = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.floor"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>floor (n, precision)](#apidoc.element.sugar.Number.floor)
- description and source-code
```javascript
floor = function (n, precision) {
  return precision ? withPrecision(n, precision, fn) : fn(n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.format"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>format (n, place)](#apidoc.element.sugar.Number.format)
- description and source-code
```javascript
format = function (n, place) {
  return numberFormat(n, place);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hex"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hex (n, pad)](#apidoc.element.sugar.Number.hex)
- description and source-code
```javascript
hex = function (n, pad) {
  return padNumber(n, pad || 1, false, 16);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hour"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hour (n)](#apidoc.element.sugar.Number.hour)
- description and source-code
```javascript
hour = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hourAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hourAfter (n, d, options)](#apidoc.element.sugar.Number.hourAfter)
- description and source-code
```javascript
hourAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hourAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hourAgo (n, d, options)](#apidoc.element.sugar.Number.hourAgo)
- description and source-code
```javascript
hourAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hourBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hourBefore (n, d, options)](#apidoc.element.sugar.Number.hourBefore)
- description and source-code
```javascript
hourBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hourFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hourFromNow (n, d, options)](#apidoc.element.sugar.Number.hourFromNow)
- description and source-code
```javascript
hourFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hours"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hours (n)](#apidoc.element.sugar.Number.hours)
- description and source-code
```javascript
hours = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hoursAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hoursAfter (n, d, options)](#apidoc.element.sugar.Number.hoursAfter)
- description and source-code
```javascript
hoursAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hoursAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hoursAgo (n, d, options)](#apidoc.element.sugar.Number.hoursAgo)
- description and source-code
```javascript
hoursAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hoursBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hoursBefore (n, d, options)](#apidoc.element.sugar.Number.hoursBefore)
- description and source-code
```javascript
hoursBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.hoursFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>hoursFromNow (n, d, options)](#apidoc.element.sugar.Number.hoursFromNow)
- description and source-code
```javascript
hoursFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.isEven"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>isEven (n)](#apidoc.element.sugar.Number.isEven)
- description and source-code
```javascript
isEven = function (n) {
  return isMultipleOf(n, 2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.isInteger"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>isInteger (n)](#apidoc.element.sugar.Number.isInteger)
- description and source-code
```javascript
isInteger = function (n) {
  return isInteger(n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.isMultipleOf"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>isMultipleOf (n, num)](#apidoc.element.sugar.Number.isMultipleOf)
- description and source-code
```javascript
isMultipleOf = function (n, num) {
  return isMultipleOf(n, num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.isOdd"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>isOdd (n)](#apidoc.element.sugar.Number.isOdd)
- description and source-code
```javascript
isOdd = function (n) {
  return isInteger(n) && !isMultipleOf(n, 2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.log"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>log (n, base)](#apidoc.element.sugar.Number.log)
- description and source-code
```javascript
log = function (n, base) {
  return Math.log(n) / (base ? Math.log(base) : 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.metric"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>metric (n, precision, units)](#apidoc.element.sugar.Number.metric)
- description and source-code
```javascript
metric = function (n, precision, units) {
  if (units === 'all') {
    units = METRIC_UNITS_FULL;
  } else if (!units) {
    units = METRIC_UNITS_SHORT;
  }
  return abbreviateNumber(n, precision, units);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecond"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecond (n)](#apidoc.element.sugar.Number.millisecond)
- description and source-code
```javascript
millisecond = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondAfter (n, d, options)](#apidoc.element.sugar.Number.millisecondAfter)
- description and source-code
```javascript
millisecondAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondAgo (n, d, options)](#apidoc.element.sugar.Number.millisecondAgo)
- description and source-code
```javascript
millisecondAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondBefore (n, d, options)](#apidoc.element.sugar.Number.millisecondBefore)
- description and source-code
```javascript
millisecondBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondFromNow (n, d, options)](#apidoc.element.sugar.Number.millisecondFromNow)
- description and source-code
```javascript
millisecondFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.milliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>milliseconds (n)](#apidoc.element.sugar.Number.milliseconds)
- description and source-code
```javascript
milliseconds = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsAfter (n, d, options)](#apidoc.element.sugar.Number.millisecondsAfter)
- description and source-code
```javascript
millisecondsAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsAgo (n, d, options)](#apidoc.element.sugar.Number.millisecondsAgo)
- description and source-code
```javascript
millisecondsAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsBefore (n, d, options)](#apidoc.element.sugar.Number.millisecondsBefore)
- description and source-code
```javascript
millisecondsBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.millisecondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>millisecondsFromNow (n, d, options)](#apidoc.element.sugar.Number.millisecondsFromNow)
- description and source-code
```javascript
millisecondsFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minute"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minute (n)](#apidoc.element.sugar.Number.minute)
- description and source-code
```javascript
minute = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minuteAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minuteAfter (n, d, options)](#apidoc.element.sugar.Number.minuteAfter)
- description and source-code
```javascript
minuteAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minuteAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minuteAgo (n, d, options)](#apidoc.element.sugar.Number.minuteAgo)
- description and source-code
```javascript
minuteAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minuteBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minuteBefore (n, d, options)](#apidoc.element.sugar.Number.minuteBefore)
- description and source-code
```javascript
minuteBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minuteFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minuteFromNow (n, d, options)](#apidoc.element.sugar.Number.minuteFromNow)
- description and source-code
```javascript
minuteFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minutes"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minutes (n)](#apidoc.element.sugar.Number.minutes)
- description and source-code
```javascript
minutes = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minutesAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minutesAfter (n, d, options)](#apidoc.element.sugar.Number.minutesAfter)
- description and source-code
```javascript
minutesAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minutesAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minutesAgo (n, d, options)](#apidoc.element.sugar.Number.minutesAgo)
- description and source-code
```javascript
minutesAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minutesBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minutesBefore (n, d, options)](#apidoc.element.sugar.Number.minutesBefore)
- description and source-code
```javascript
minutesBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.minutesFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>minutesFromNow (n, d, options)](#apidoc.element.sugar.Number.minutesFromNow)
- description and source-code
```javascript
minutesFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.month"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>month (n)](#apidoc.element.sugar.Number.month)
- description and source-code
```javascript
month = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthAfter (n, d, options)](#apidoc.element.sugar.Number.monthAfter)
- description and source-code
```javascript
monthAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthAgo (n, d, options)](#apidoc.element.sugar.Number.monthAgo)
- description and source-code
```javascript
monthAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthBefore (n, d, options)](#apidoc.element.sugar.Number.monthBefore)
- description and source-code
```javascript
monthBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthFromNow (n, d, options)](#apidoc.element.sugar.Number.monthFromNow)
- description and source-code
```javascript
monthFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.months"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>months (n)](#apidoc.element.sugar.Number.months)
- description and source-code
```javascript
months = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthsAfter (n, d, options)](#apidoc.element.sugar.Number.monthsAfter)
- description and source-code
```javascript
monthsAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthsAgo (n, d, options)](#apidoc.element.sugar.Number.monthsAgo)
- description and source-code
```javascript
monthsAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthsBefore (n, d, options)](#apidoc.element.sugar.Number.monthsBefore)
- description and source-code
```javascript
monthsBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.monthsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>monthsFromNow (n, d, options)](#apidoc.element.sugar.Number.monthsFromNow)
- description and source-code
```javascript
monthsFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.ordinalize"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>ordinalize (n)](#apidoc.element.sugar.Number.ordinalize)
- description and source-code
```javascript
ordinalize = function (n) {
  var num = abs(n), last = +num.toString().slice(-2);
  return n + getOrdinalSuffix(last);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.pad"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>pad (n, place, sign, base)](#apidoc.element.sugar.Number.pad)
- description and source-code
```javascript
pad = function (n, place, sign, base) {
  return padNumber(n, place, sign, base);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.pow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>pow (n, arg)](#apidoc.element.sugar.Number.pow)
- description and source-code
```javascript
pow = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.random"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>random (n1, n2)](#apidoc.element.sugar.Number.random)
- description and source-code
```javascript
random = function (n1, n2) {
  var minNum, maxNum;
  if (arguments.length == 1) n2 = n1, n1 = 0;
  minNum = min(n1 || 0, isUndefined(n2) ? 1 : n2);
  maxNum = max(n1 || 0, isUndefined(n2) ? 1 : n2) + 1;
  return trunc((Math.random() * (maxNum - minNum)) + minNum);
}
```
- example usage
```shell
...

Sugar now makes it easy to define your own methods. This is aimed at developers
hoping to release their own plugins with Sugar. After defining methods, they can
be extended or used as chainables just like other methods:

'''javascript
Sugar.Number.defineStatic('randomish', function () {
  if (Math.random() > .5) {
    return Math.random();
  } else {
    return 1;
  }
});

Sugar.Number.defineInstance({
...
```

#### <a name="apidoc.element.sugar.Number.range"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>range (start, end)](#apidoc.element.sugar.Number.range)
- description and source-code
```javascript
range = function (start, end) {
  return new Range(start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.round"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>round (n, precision)](#apidoc.element.sugar.Number.round)
- description and source-code
```javascript
round = function (n, precision) {
  return precision ? withPrecision(n, precision, fn) : fn(n);
}
```
- example usage
```shell
...
browser. All methods will be defined on this object and can be called as normal.
Requiring an individual method will define it on 'Sugar' and additionally return
a reference to its static form that can be called immediately:

'''javascript
// Require all modules
var Sugar = require('sugar');
Sugar.Number.round(3.1415);

// Require the Number module
var Sugar = require('sugar/number');
Sugar.Number.round(3.1415);

// Require only the "round" method
var round = require('sugar/number/round');
...
```

#### <a name="apidoc.element.sugar.Number.second"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>second (n)](#apidoc.element.sugar.Number.second)
- description and source-code
```javascript
second = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondAfter (n, d, options)](#apidoc.element.sugar.Number.secondAfter)
- description and source-code
```javascript
secondAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondAgo (n, d, options)](#apidoc.element.sugar.Number.secondAgo)
- description and source-code
```javascript
secondAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondBefore (n, d, options)](#apidoc.element.sugar.Number.secondBefore)
- description and source-code
```javascript
secondBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondFromNow (n, d, options)](#apidoc.element.sugar.Number.secondFromNow)
- description and source-code
```javascript
secondFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.seconds"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>seconds (n)](#apidoc.element.sugar.Number.seconds)
- description and source-code
```javascript
seconds = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondsAfter (n, d, options)](#apidoc.element.sugar.Number.secondsAfter)
- description and source-code
```javascript
secondsAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondsAgo (n, d, options)](#apidoc.element.sugar.Number.secondsAgo)
- description and source-code
```javascript
secondsAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondsBefore (n, d, options)](#apidoc.element.sugar.Number.secondsBefore)
- description and source-code
```javascript
secondsBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.secondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>secondsFromNow (n, d, options)](#apidoc.element.sugar.Number.secondsFromNow)
- description and source-code
```javascript
secondsFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.sin"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>sin (n, arg)](#apidoc.element.sugar.Number.sin)
- description and source-code
```javascript
sin = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.sqrt"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>sqrt (n, arg)](#apidoc.element.sugar.Number.sqrt)
- description and source-code
```javascript
sqrt = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.tan"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>tan (n, arg)](#apidoc.element.sugar.Number.tan)
- description and source-code
```javascript
tan = function (n, arg) {
  // Note that .valueOf() here is only required due to a
  // very strange bug in iOS7 that only occurs occasionally
  // in which Math.abs() called on non-primitive numbers
  // returns a completely different number (Issue #400)
  return Math[name](n.valueOf(), arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.times"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>times (n, fn)](#apidoc.element.sugar.Number.times)
- description and source-code
```javascript
times = function (n, fn) {
  var arr, result;
  for(var i = 0; i < n; i++) {
    result = fn.call(n, i);
    if (isDefined(result)) {
      if (!arr) {
        arr = [];
      }
      arr.push(result);
    }
  }
  return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.toNumber"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>toNumber (n)](#apidoc.element.sugar.Number.toNumber)
- description and source-code
```javascript
toNumber = function (n) {
  return n.valueOf();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.upto"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>upto (n, num, step, fn)](#apidoc.element.sugar.Number.upto)
- description and source-code
```javascript
upto = function (n, num, step, fn) {
  return rangeEvery(new Range(n, num), step, false, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.week"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>week (n)](#apidoc.element.sugar.Number.week)
- description and source-code
```javascript
week = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weekAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weekAfter (n, d, options)](#apidoc.element.sugar.Number.weekAfter)
- description and source-code
```javascript
weekAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weekAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weekAgo (n, d, options)](#apidoc.element.sugar.Number.weekAgo)
- description and source-code
```javascript
weekAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weekBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weekBefore (n, d, options)](#apidoc.element.sugar.Number.weekBefore)
- description and source-code
```javascript
weekBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weekFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weekFromNow (n, d, options)](#apidoc.element.sugar.Number.weekFromNow)
- description and source-code
```javascript
weekFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weeks"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weeks (n)](#apidoc.element.sugar.Number.weeks)
- description and source-code
```javascript
weeks = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weeksAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weeksAfter (n, d, options)](#apidoc.element.sugar.Number.weeksAfter)
- description and source-code
```javascript
weeksAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weeksAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weeksAgo (n, d, options)](#apidoc.element.sugar.Number.weeksAgo)
- description and source-code
```javascript
weeksAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weeksBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weeksBefore (n, d, options)](#apidoc.element.sugar.Number.weeksBefore)
- description and source-code
```javascript
weeksBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.weeksFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>weeksFromNow (n, d, options)](#apidoc.element.sugar.Number.weeksFromNow)
- description and source-code
```javascript
weeksFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.year"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>year (n)](#apidoc.element.sugar.Number.year)
- description and source-code
```javascript
year = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearAfter (n, d, options)](#apidoc.element.sugar.Number.yearAfter)
- description and source-code
```javascript
yearAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearAgo (n, d, options)](#apidoc.element.sugar.Number.yearAgo)
- description and source-code
```javascript
yearAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearBefore (n, d, options)](#apidoc.element.sugar.Number.yearBefore)
- description and source-code
```javascript
yearBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearFromNow (n, d, options)](#apidoc.element.sugar.Number.yearFromNow)
- description and source-code
```javascript
yearFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.years"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>years (n)](#apidoc.element.sugar.Number.years)
- description and source-code
```javascript
years = function (n) {
  return round(n * unit.multiplier);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearsAfter (n, d, options)](#apidoc.element.sugar.Number.yearsAfter)
- description and source-code
```javascript
yearsAfter = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearsAgo (n, d, options)](#apidoc.element.sugar.Number.yearsAgo)
- description and source-code
```javascript
yearsAgo = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearsBefore (n, d, options)](#apidoc.element.sugar.Number.yearsBefore)
- description and source-code
```javascript
yearsBefore = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, -n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.yearsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.</span>yearsFromNow (n, d, options)](#apidoc.element.sugar.Number.yearsFromNow)
- description and source-code
```javascript
yearsFromNow = function (n, d, options) {
  return advanceDate(createDate(d, options, true), name, n);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Number.prototype"></a>[module sugar.Number.prototype](#apidoc.module.sugar.Number.prototype)

#### <a name="apidoc.element.sugar.Number.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Number.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Number.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Number.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Number.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.abbr"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>abbr ()](#apidoc.element.sugar.Number.prototype.abbr)
- description and source-code
```javascript
abbr = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.abs"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>abs ()](#apidoc.element.sugar.Number.prototype.abs)
- description and source-code
```javascript
abs = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.acos"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>acos ()](#apidoc.element.sugar.Number.prototype.acos)
- description and source-code
```javascript
acos = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>add ()](#apidoc.element.sugar.Number.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Number.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>addAll ()](#apidoc.element.sugar.Number.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.asin"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>asin ()](#apidoc.element.sugar.Number.prototype.asin)
- description and source-code
```javascript
asin = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.atan"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>atan ()](#apidoc.element.sugar.Number.prototype.atan)
- description and source-code
```javascript
atan = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>average ()](#apidoc.element.sugar.Number.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.bytes"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>bytes ()](#apidoc.element.sugar.Number.prototype.bytes)
- description and source-code
```javascript
bytes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.cap"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>cap ()](#apidoc.element.sugar.Number.prototype.cap)
- description and source-code
```javascript
cap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.ceil"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>ceil ()](#apidoc.element.sugar.Number.prototype.ceil)
- description and source-code
```javascript
ceil = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.chr"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>chr ()](#apidoc.element.sugar.Number.prototype.chr)
- description and source-code
```javascript
chr = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.clamp"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>clamp ()](#apidoc.element.sugar.Number.prototype.clamp)
- description and source-code
```javascript
clamp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>clone ()](#apidoc.element.sugar.Number.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.cos"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>cos ()](#apidoc.element.sugar.Number.prototype.cos)
- description and source-code
```javascript
cos = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>count ()](#apidoc.element.sugar.Number.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.day"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>day ()](#apidoc.element.sugar.Number.prototype.day)
- description and source-code
```javascript
day = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.dayAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayAfter ()](#apidoc.element.sugar.Number.prototype.dayAfter)
- description and source-code
```javascript
dayAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.dayAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayAgo ()](#apidoc.element.sugar.Number.prototype.dayAgo)
- description and source-code
```javascript
dayAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.dayBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayBefore ()](#apidoc.element.sugar.Number.prototype.dayBefore)
- description and source-code
```javascript
dayBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.dayFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>dayFromNow ()](#apidoc.element.sugar.Number.prototype.dayFromNow)
- description and source-code
```javascript
dayFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.days"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>days ()](#apidoc.element.sugar.Number.prototype.days)
- description and source-code
```javascript
days = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.daysAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysAfter ()](#apidoc.element.sugar.Number.prototype.daysAfter)
- description and source-code
```javascript
daysAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.daysAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysAgo ()](#apidoc.element.sugar.Number.prototype.daysAgo)
- description and source-code
```javascript
daysAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.daysBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysBefore ()](#apidoc.element.sugar.Number.prototype.daysBefore)
- description and source-code
```javascript
daysBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.daysFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>daysFromNow ()](#apidoc.element.sugar.Number.prototype.daysFromNow)
- description and source-code
```javascript
daysFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>defaults ()](#apidoc.element.sugar.Number.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.downto"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>downto ()](#apidoc.element.sugar.Number.prototype.downto)
- description and source-code
```javascript
downto = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.duration"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>duration ()](#apidoc.element.sugar.Number.prototype.duration)
- description and source-code
```javascript
duration = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>every ()](#apidoc.element.sugar.Number.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>exclude ()](#apidoc.element.sugar.Number.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.exp"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>exp ()](#apidoc.element.sugar.Number.prototype.exp)
- description and source-code
```javascript
exp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>filter ()](#apidoc.element.sugar.Number.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>find ()](#apidoc.element.sugar.Number.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.floor"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>floor ()](#apidoc.element.sugar.Number.prototype.floor)
- description and source-code
```javascript
floor = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>forEach ()](#apidoc.element.sugar.Number.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.format"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>format ()](#apidoc.element.sugar.Number.prototype.format)
- description and source-code
```javascript
format = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>get ()](#apidoc.element.sugar.Number.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Number.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>has ()](#apidoc.element.sugar.Number.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Number.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hex"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hex ()](#apidoc.element.sugar.Number.prototype.hex)
- description and source-code
```javascript
hex = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hour"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hour ()](#apidoc.element.sugar.Number.prototype.hour)
- description and source-code
```javascript
hour = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hourAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourAfter ()](#apidoc.element.sugar.Number.prototype.hourAfter)
- description and source-code
```javascript
hourAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hourAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourAgo ()](#apidoc.element.sugar.Number.prototype.hourAgo)
- description and source-code
```javascript
hourAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hourBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourBefore ()](#apidoc.element.sugar.Number.prototype.hourBefore)
- description and source-code
```javascript
hourBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hourFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hourFromNow ()](#apidoc.element.sugar.Number.prototype.hourFromNow)
- description and source-code
```javascript
hourFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hours"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hours ()](#apidoc.element.sugar.Number.prototype.hours)
- description and source-code
```javascript
hours = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hoursAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursAfter ()](#apidoc.element.sugar.Number.prototype.hoursAfter)
- description and source-code
```javascript
hoursAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hoursAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursAgo ()](#apidoc.element.sugar.Number.prototype.hoursAgo)
- description and source-code
```javascript
hoursAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hoursBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursBefore ()](#apidoc.element.sugar.Number.prototype.hoursBefore)
- description and source-code
```javascript
hoursBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.hoursFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>hoursFromNow ()](#apidoc.element.sugar.Number.prototype.hoursFromNow)
- description and source-code
```javascript
hoursFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>intersect ()](#apidoc.element.sugar.Number.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>invert ()](#apidoc.element.sugar.Number.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isArguments ()](#apidoc.element.sugar.Number.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isArray ()](#apidoc.element.sugar.Number.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isBoolean ()](#apidoc.element.sugar.Number.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isDate ()](#apidoc.element.sugar.Number.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isEmpty ()](#apidoc.element.sugar.Number.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isEqual ()](#apidoc.element.sugar.Number.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isError ()](#apidoc.element.sugar.Number.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isEven"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isEven ()](#apidoc.element.sugar.Number.prototype.isEven)
- description and source-code
```javascript
isEven = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isFunction ()](#apidoc.element.sugar.Number.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isInteger"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isInteger ()](#apidoc.element.sugar.Number.prototype.isInteger)
- description and source-code
```javascript
isInteger = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isMap ()](#apidoc.element.sugar.Number.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isMultipleOf"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isMultipleOf ()](#apidoc.element.sugar.Number.prototype.isMultipleOf)
- description and source-code
```javascript
isMultipleOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isNumber ()](#apidoc.element.sugar.Number.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isObject ()](#apidoc.element.sugar.Number.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isOdd"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isOdd ()](#apidoc.element.sugar.Number.prototype.isOdd)
- description and source-code
```javascript
isOdd = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Number.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isRegExp ()](#apidoc.element.sugar.Number.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isSet ()](#apidoc.element.sugar.Number.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>isString ()](#apidoc.element.sugar.Number.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>keys ()](#apidoc.element.sugar.Number.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>least ()](#apidoc.element.sugar.Number.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.log"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>log ()](#apidoc.element.sugar.Number.prototype.log)
- description and source-code
```javascript
log = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>map ()](#apidoc.element.sugar.Number.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>max ()](#apidoc.element.sugar.Number.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>median ()](#apidoc.element.sugar.Number.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>merge ()](#apidoc.element.sugar.Number.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>mergeAll ()](#apidoc.element.sugar.Number.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.metric"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>metric ()](#apidoc.element.sugar.Number.prototype.metric)
- description and source-code
```javascript
metric = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecond"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecond ()](#apidoc.element.sugar.Number.prototype.millisecond)
- description and source-code
```javascript
millisecond = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondAfter ()](#apidoc.element.sugar.Number.prototype.millisecondAfter)
- description and source-code
```javascript
millisecondAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondAgo ()](#apidoc.element.sugar.Number.prototype.millisecondAgo)
- description and source-code
```javascript
millisecondAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondBefore ()](#apidoc.element.sugar.Number.prototype.millisecondBefore)
- description and source-code
```javascript
millisecondBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondFromNow ()](#apidoc.element.sugar.Number.prototype.millisecondFromNow)
- description and source-code
```javascript
millisecondFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.milliseconds"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>milliseconds ()](#apidoc.element.sugar.Number.prototype.milliseconds)
- description and source-code
```javascript
milliseconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsAfter ()](#apidoc.element.sugar.Number.prototype.millisecondsAfter)
- description and source-code
```javascript
millisecondsAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsAgo ()](#apidoc.element.sugar.Number.prototype.millisecondsAgo)
- description and source-code
```javascript
millisecondsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsBefore ()](#apidoc.element.sugar.Number.prototype.millisecondsBefore)
- description and source-code
```javascript
millisecondsBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.millisecondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>millisecondsFromNow ()](#apidoc.element.sugar.Number.prototype.millisecondsFromNow)
- description and source-code
```javascript
millisecondsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>min ()](#apidoc.element.sugar.Number.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minute"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minute ()](#apidoc.element.sugar.Number.prototype.minute)
- description and source-code
```javascript
minute = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minuteAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteAfter ()](#apidoc.element.sugar.Number.prototype.minuteAfter)
- description and source-code
```javascript
minuteAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minuteAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteAgo ()](#apidoc.element.sugar.Number.prototype.minuteAgo)
- description and source-code
```javascript
minuteAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minuteBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteBefore ()](#apidoc.element.sugar.Number.prototype.minuteBefore)
- description and source-code
```javascript
minuteBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minuteFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minuteFromNow ()](#apidoc.element.sugar.Number.prototype.minuteFromNow)
- description and source-code
```javascript
minuteFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minutes"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutes ()](#apidoc.element.sugar.Number.prototype.minutes)
- description and source-code
```javascript
minutes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minutesAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesAfter ()](#apidoc.element.sugar.Number.prototype.minutesAfter)
- description and source-code
```javascript
minutesAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minutesAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesAgo ()](#apidoc.element.sugar.Number.prototype.minutesAgo)
- description and source-code
```javascript
minutesAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minutesBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesBefore ()](#apidoc.element.sugar.Number.prototype.minutesBefore)
- description and source-code
```javascript
minutesBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.minutesFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>minutesFromNow ()](#apidoc.element.sugar.Number.prototype.minutesFromNow)
- description and source-code
```javascript
minutesFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.month"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>month ()](#apidoc.element.sugar.Number.prototype.month)
- description and source-code
```javascript
month = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthAfter ()](#apidoc.element.sugar.Number.prototype.monthAfter)
- description and source-code
```javascript
monthAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthAgo ()](#apidoc.element.sugar.Number.prototype.monthAgo)
- description and source-code
```javascript
monthAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthBefore ()](#apidoc.element.sugar.Number.prototype.monthBefore)
- description and source-code
```javascript
monthBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthFromNow ()](#apidoc.element.sugar.Number.prototype.monthFromNow)
- description and source-code
```javascript
monthFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.months"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>months ()](#apidoc.element.sugar.Number.prototype.months)
- description and source-code
```javascript
months = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsAfter ()](#apidoc.element.sugar.Number.prototype.monthsAfter)
- description and source-code
```javascript
monthsAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsAgo ()](#apidoc.element.sugar.Number.prototype.monthsAgo)
- description and source-code
```javascript
monthsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsBefore ()](#apidoc.element.sugar.Number.prototype.monthsBefore)
- description and source-code
```javascript
monthsBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.monthsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>monthsFromNow ()](#apidoc.element.sugar.Number.prototype.monthsFromNow)
- description and source-code
```javascript
monthsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>most ()](#apidoc.element.sugar.Number.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>none ()](#apidoc.element.sugar.Number.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.ordinalize"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>ordinalize ()](#apidoc.element.sugar.Number.prototype.ordinalize)
- description and source-code
```javascript
ordinalize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.pad"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>pad ()](#apidoc.element.sugar.Number.prototype.pad)
- description and source-code
```javascript
pad = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.pow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>pow ()](#apidoc.element.sugar.Number.prototype.pow)
- description and source-code
```javascript
pow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Number.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>reduce ()](#apidoc.element.sugar.Number.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>reject ()](#apidoc.element.sugar.Number.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>remove ()](#apidoc.element.sugar.Number.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Number.prototype.round"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>round ()](#apidoc.element.sugar.Number.prototype.round)
- description and source-code
```javascript
round = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
browser. All methods will be defined on this object and can be called as normal.
Requiring an individual method will define it on 'Sugar' and additionally return
a reference to its static form that can be called immediately:

'''javascript
// Require all modules
var Sugar = require('sugar');
Sugar.Number.round(3.1415);

// Require the Number module
var Sugar = require('sugar/number');
Sugar.Number.round(3.1415);

// Require only the "round" method
var round = require('sugar/number/round');
...
```

#### <a name="apidoc.element.sugar.Number.prototype.second"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>second ()](#apidoc.element.sugar.Number.prototype.second)
- description and source-code
```javascript
second = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondAfter ()](#apidoc.element.sugar.Number.prototype.secondAfter)
- description and source-code
```javascript
secondAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondAgo ()](#apidoc.element.sugar.Number.prototype.secondAgo)
- description and source-code
```javascript
secondAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondBefore ()](#apidoc.element.sugar.Number.prototype.secondBefore)
- description and source-code
```javascript
secondBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondFromNow ()](#apidoc.element.sugar.Number.prototype.secondFromNow)
- description and source-code
```javascript
secondFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.seconds"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>seconds ()](#apidoc.element.sugar.Number.prototype.seconds)
- description and source-code
```javascript
seconds = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsAfter ()](#apidoc.element.sugar.Number.prototype.secondsAfter)
- description and source-code
```javascript
secondsAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsAgo ()](#apidoc.element.sugar.Number.prototype.secondsAgo)
- description and source-code
```javascript
secondsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsBefore ()](#apidoc.element.sugar.Number.prototype.secondsBefore)
- description and source-code
```javascript
secondsBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.secondsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>secondsFromNow ()](#apidoc.element.sugar.Number.prototype.secondsFromNow)
- description and source-code
```javascript
secondsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>select ()](#apidoc.element.sugar.Number.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>set ()](#apidoc.element.sugar.Number.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Number.prototype.sin"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>sin ()](#apidoc.element.sugar.Number.prototype.sin)
- description and source-code
```javascript
sin = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>size ()](#apidoc.element.sugar.Number.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>some ()](#apidoc.element.sugar.Number.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.sqrt"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>sqrt ()](#apidoc.element.sugar.Number.prototype.sqrt)
- description and source-code
```javascript
sqrt = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>subtract ()](#apidoc.element.sugar.Number.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>sum ()](#apidoc.element.sugar.Number.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.tan"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>tan ()](#apidoc.element.sugar.Number.prototype.tan)
- description and source-code
```javascript
tan = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>tap ()](#apidoc.element.sugar.Number.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.times"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>times ()](#apidoc.element.sugar.Number.prototype.times)
- description and source-code
```javascript
times = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.toExponential"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toExponential ()](#apidoc.element.sugar.Number.prototype.toExponential)
- description and source-code
```javascript
toExponential = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.toFixed"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toFixed ()](#apidoc.element.sugar.Number.prototype.toFixed)
- description and source-code
```javascript
toFixed = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  if (num === 1 && format === 'past')   return 'wczoraj';
  if (num === 1 && format === 'future') return 'jutro';
  if (num === 2 && format === 'past')   return 'przedwczoraj';
  if (num === 2 && format === 'future') return 'pojutrze';
}

var mult;
var last  = +num.toFixed(0).slice(-1);
var last2 = +num.toFixed(0).slice(-2);
switch (true) {
  case num === 1:                  mult = 0; break;
  case last2 >= 12 && last2 <= 14: mult = 2; break;
  case last  >=  2 && last  <=  4: mult = 1; break;
  default:                         mult = 2;
}
...
```

#### <a name="apidoc.element.sugar.Number.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Number.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toNumber ()](#apidoc.element.sugar.Number.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.toPrecision"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toPrecision ()](#apidoc.element.sugar.Number.prototype.toPrecision)
- description and source-code
```javascript
toPrecision = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toQueryString ()](#apidoc.element.sugar.Number.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>toString ()](#apidoc.element.sugar.Number.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.Number.prototype.upto"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>upto ()](#apidoc.element.sugar.Number.prototype.upto)
- description and source-code
```javascript
upto = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>values ()](#apidoc.element.sugar.Number.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.week"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>week ()](#apidoc.element.sugar.Number.prototype.week)
- description and source-code
```javascript
week = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weekAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekAfter ()](#apidoc.element.sugar.Number.prototype.weekAfter)
- description and source-code
```javascript
weekAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weekAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekAgo ()](#apidoc.element.sugar.Number.prototype.weekAgo)
- description and source-code
```javascript
weekAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weekBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekBefore ()](#apidoc.element.sugar.Number.prototype.weekBefore)
- description and source-code
```javascript
weekBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weekFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weekFromNow ()](#apidoc.element.sugar.Number.prototype.weekFromNow)
- description and source-code
```javascript
weekFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weeks"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeks ()](#apidoc.element.sugar.Number.prototype.weeks)
- description and source-code
```javascript
weeks = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weeksAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksAfter ()](#apidoc.element.sugar.Number.prototype.weeksAfter)
- description and source-code
```javascript
weeksAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weeksAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksAgo ()](#apidoc.element.sugar.Number.prototype.weeksAgo)
- description and source-code
```javascript
weeksAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weeksBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksBefore ()](#apidoc.element.sugar.Number.prototype.weeksBefore)
- description and source-code
```javascript
weeksBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.weeksFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>weeksFromNow ()](#apidoc.element.sugar.Number.prototype.weeksFromNow)
- description and source-code
```javascript
weeksFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.year"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>year ()](#apidoc.element.sugar.Number.prototype.year)
- description and source-code
```javascript
year = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearAfter ()](#apidoc.element.sugar.Number.prototype.yearAfter)
- description and source-code
```javascript
yearAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearAgo ()](#apidoc.element.sugar.Number.prototype.yearAgo)
- description and source-code
```javascript
yearAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearBefore ()](#apidoc.element.sugar.Number.prototype.yearBefore)
- description and source-code
```javascript
yearBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearFromNow ()](#apidoc.element.sugar.Number.prototype.yearFromNow)
- description and source-code
```javascript
yearFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.years"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>years ()](#apidoc.element.sugar.Number.prototype.years)
- description and source-code
```javascript
years = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearsAfter"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsAfter ()](#apidoc.element.sugar.Number.prototype.yearsAfter)
- description and source-code
```javascript
yearsAfter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearsAgo"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsAgo ()](#apidoc.element.sugar.Number.prototype.yearsAgo)
- description and source-code
```javascript
yearsAgo = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearsBefore"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsBefore ()](#apidoc.element.sugar.Number.prototype.yearsBefore)
- description and source-code
```javascript
yearsBefore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Number.prototype.yearsFromNow"></a>[function <span class="apidocSignatureSpan">sugar.Number.prototype.</span>yearsFromNow ()](#apidoc.element.sugar.Number.prototype.yearsFromNow)
- description and source-code
```javascript
yearsFromNow = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Object"></a>[module sugar.Object](#apidoc.module.sugar.Object)

#### <a name="apidoc.element.sugar.Object.Object"></a>[function <span class="apidocSignatureSpan">sugar.</span>Object {{signature}}](#apidoc.element.sugar.Object.Object)
- description and source-code
```javascript
SugarObject
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.add"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>add (obj1, obj2, opts)](#apidoc.element.sugar.Object.add)
- description and source-code
```javascript
add = function (obj1, obj2, opts) {
  return mergeWithOptions(clone(obj1), obj2, opts);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Object.addAll"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>addAll (obj, sources, opts)](#apidoc.element.sugar.Object.addAll)
- description and source-code
```javascript
addAll = function (obj, sources, opts) {
  return mergeAll(clone(obj), sources, opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.average"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>average (obj, map)](#apidoc.element.sugar.Object.average)
- description and source-code
```javascript
average = function (obj, map) {
  return average(obj, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.clone"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>clone (obj, deep)](#apidoc.element.sugar.Object.clone)
- description and source-code
```javascript
clone = function (obj, deep) {
  return clone(obj, deep);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.count"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>count (obj, f)](#apidoc.element.sugar.Object.count)
- description and source-code
```javascript
count = function (obj, f) {
  return objectCount(obj, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.defaults"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>defaults (target, sources, opts)](#apidoc.element.sugar.Object.defaults)
- description and source-code
```javascript
defaults = function (target, sources, opts) {
  return defaults(target, sources, opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.every"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>every (obj, f)](#apidoc.element.sugar.Object.every)
- description and source-code
```javascript
every = function (obj, f) {
  var matcher = getMatcher(f);
  return nativeFn.call(getKeys(obj), function(key) {
    return matcher(obj[key], key, obj);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>exclude (obj, f)](#apidoc.element.sugar.Object.exclude)
- description and source-code
```javascript
exclude = function (obj, f) {
  return objectExclude(obj, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.filter"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>filter (obj, f)](#apidoc.element.sugar.Object.filter)
- description and source-code
```javascript
filter = function (obj, f) {
  return objectFilter(obj, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.find"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>find (obj, f)](#apidoc.element.sugar.Object.find)
- description and source-code
```javascript
find = function (obj, f) {
  var matcher = getMatcher(f);
  return nativeFn.call(getKeys(obj), function(key) {
    return matcher(obj[key], key, obj);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.forEach"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>forEach (obj, fn)](#apidoc.element.sugar.Object.forEach)
- description and source-code
```javascript
forEach = function (obj, fn) {
  return objectForEach(obj, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.fromQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>fromQueryString (obj, options)](#apidoc.element.sugar.Object.fromQueryString)
- description and source-code
```javascript
fromQueryString = function (obj, options) {
  return fromQueryStringWithOptions(obj, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.get"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>get (obj, key, any)](#apidoc.element.sugar.Object.get)
- description and source-code
```javascript
get = function (obj, key, any) {
  return deepGetProperty(obj, key, any);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Object.has"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>has (obj, key, any)](#apidoc.element.sugar.Object.has)
- description and source-code
```javascript
has = function (obj, key, any) {
  return deepHasProperty(obj, key, any);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>intersect (obj1, obj2)](#apidoc.element.sugar.Object.intersect)
- description and source-code
```javascript
intersect = function (obj1, obj2) {
  return objectIntersectOrSubtract(obj1, obj2, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.invert"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>invert (obj, multi)](#apidoc.element.sugar.Object.invert)
- description and source-code
```javascript
invert = function (obj, multi) {
  var result = {};
  multi = multi === true;
  forEachProperty(obj, function(val, key) {
    if (hasOwn(result, val) && multi) {
      result[val].push(key);
    } else if (multi) {
      result[val] = [key];
    } else {
      result[val] = key;
    }
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isArguments (obj)](#apidoc.element.sugar.Object.isArguments)
- description and source-code
```javascript
isArguments = function (obj) {
  return isArguments(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isArray"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isArray ()](#apidoc.element.sugar.Object.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isBoolean (obj)](#apidoc.element.sugar.Object.isBoolean)
- description and source-code
```javascript
isBoolean = function (obj) {
  var t = typeof obj;
  return t === type || t === 'object' && isClass(obj, className);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isDate"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isDate (obj, str)](#apidoc.element.sugar.Object.isDate)
- description and source-code
```javascript
isDate = function (obj, str) {
  // perf: Returning up front on instanceof appears to be slower.
  return isClass(obj, className, str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isEmpty (obj)](#apidoc.element.sugar.Object.isEmpty)
- description and source-code
```javascript
isEmpty = function (obj) {
  return objectSize(obj) === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isEqual (obj1, obj2)](#apidoc.element.sugar.Object.isEqual)
- description and source-code
```javascript
isEqual = function (obj1, obj2) {
  return isEqual(obj1, obj2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isError"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isError (obj, str)](#apidoc.element.sugar.Object.isError)
- description and source-code
```javascript
isError = function (obj, str) {
  // perf: Returning up front on instanceof appears to be slower.
  return isClass(obj, className, str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isFunction (obj, str)](#apidoc.element.sugar.Object.isFunction)
- description and source-code
```javascript
isFunction = function (obj, str) {
  // perf: Returning up front on instanceof appears to be slower.
  return isClass(obj, className, str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isMap"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isMap (obj, str)](#apidoc.element.sugar.Object.isMap)
- description and source-code
```javascript
isMap = function (obj, str) {
  // perf: Returning up front on instanceof appears to be slower.
  return isClass(obj, className, str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isNumber (obj)](#apidoc.element.sugar.Object.isNumber)
- description and source-code
```javascript
isNumber = function (obj) {
  var t = typeof obj;
  return t === type || t === 'object' && isClass(obj, className);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isObject"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isObject (obj)](#apidoc.element.sugar.Object.isObject)
- description and source-code
```javascript
isObject = function (obj) {
  return isPlainObject(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isRegExp (obj, str)](#apidoc.element.sugar.Object.isRegExp)
- description and source-code
```javascript
isRegExp = function (obj, str) {
  // perf: Returning up front on instanceof appears to be slower.
  return isClass(obj, className, str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isSet"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isSet (obj, str)](#apidoc.element.sugar.Object.isSet)
- description and source-code
```javascript
isSet = function (obj, str) {
  // perf: Returning up front on instanceof appears to be slower.
  return isClass(obj, className, str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.isString"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>isString (obj)](#apidoc.element.sugar.Object.isString)
- description and source-code
```javascript
isString = function (obj) {
  var t = typeof obj;
  return t === type || t === 'object' && isClass(obj, className);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.keys"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>keys (obj)](#apidoc.element.sugar.Object.keys)
- description and source-code
```javascript
keys = function (obj) {
  return getKeys(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.least"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>least (obj, all, map)](#apidoc.element.sugar.Object.least)
- description and source-code
```javascript
least = function (obj, all, map) {
  return getLeastOrMost(obj, all, map, false, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.map"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>map (obj, map)](#apidoc.element.sugar.Object.map)
- description and source-code
```javascript
map = function (obj, map) {
  return objectMap(obj, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.max"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>max (obj, all, map)](#apidoc.element.sugar.Object.max)
- description and source-code
```javascript
max = function (obj, all, map) {
  return getMinOrMax(obj, all, map, true, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.median"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>median (obj, map)](#apidoc.element.sugar.Object.median)
- description and source-code
```javascript
median = function (obj, map) {
  return median(obj, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.merge"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>merge (target, source, opts)](#apidoc.element.sugar.Object.merge)
- description and source-code
```javascript
merge = function (target, source, opts) {
  return mergeWithOptions(target, source, opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>mergeAll (target, sources, opts)](#apidoc.element.sugar.Object.mergeAll)
- description and source-code
```javascript
mergeAll = function (target, sources, opts) {
  return mergeAll(target, sources, opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.min"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>min (obj, all, map)](#apidoc.element.sugar.Object.min)
- description and source-code
```javascript
min = function (obj, all, map) {
  return getMinOrMax(obj, all, map, false, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.most"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>most (obj, all, map)](#apidoc.element.sugar.Object.most)
- description and source-code
```javascript
most = function (obj, all, map) {
  return getLeastOrMost(obj, all, map, true, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.none"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>none (obj, f)](#apidoc.element.sugar.Object.none)
- description and source-code
```javascript
none = function (obj, f) {
  return objectNone(obj, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.reduce"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>reduce (obj, fn, init)](#apidoc.element.sugar.Object.reduce)
- description and source-code
```javascript
reduce = function (obj, fn, init) {
  return objectReduce(obj, fn, init);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.reject"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>reject (obj, f)](#apidoc.element.sugar.Object.reject)
- description and source-code
```javascript
reject = function (obj, f) {
  return objectReject(obj, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.remove"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>remove (obj, f)](#apidoc.element.sugar.Object.remove)
- description and source-code
```javascript
remove = function (obj, f) {
  return objectRemove(obj, f);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Object.select"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>select (obj, f)](#apidoc.element.sugar.Object.select)
- description and source-code
```javascript
select = function (obj, f) {
  return objectSelect(obj, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.set"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>set (obj, key, val)](#apidoc.element.sugar.Object.set)
- description and source-code
```javascript
set = function (obj, key, val) {
  return deepSetProperty(obj, key, val);
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Object.size"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>size (obj)](#apidoc.element.sugar.Object.size)
- description and source-code
```javascript
size = function (obj) {
  return objectSize(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.some"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>some (obj, f)](#apidoc.element.sugar.Object.some)
- description and source-code
```javascript
some = function (obj, f) {
  var matcher = getMatcher(f);
  return nativeFn.call(getKeys(obj), function(key) {
    return matcher(obj[key], key, obj);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>subtract (obj1, obj2)](#apidoc.element.sugar.Object.subtract)
- description and source-code
```javascript
subtract = function (obj1, obj2) {
  return objectIntersectOrSubtract(obj1, obj2, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.sum"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>sum (obj, map)](#apidoc.element.sugar.Object.sum)
- description and source-code
```javascript
sum = function (obj, map) {
  return sum(obj, map);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.tap"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>tap (obj, arg)](#apidoc.element.sugar.Object.tap)
- description and source-code
```javascript
tap = function (obj, arg) {
  return tap(obj, arg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>toQueryString (obj, options)](#apidoc.element.sugar.Object.toQueryString)
- description and source-code
```javascript
toQueryString = function (obj, options) {
  return toQueryStringWithOptions(obj, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.values"></a>[function <span class="apidocSignatureSpan">sugar.Object.</span>values (obj)](#apidoc.element.sugar.Object.values)
- description and source-code
```javascript
values = function (obj) {
  return getValues(obj);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.Object.prototype"></a>[module sugar.Object.prototype](#apidoc.module.sugar.Object.prototype)

#### <a name="apidoc.element.sugar.Object.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.Object.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.Object.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.Object.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.Object.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>add ()](#apidoc.element.sugar.Object.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.Object.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>addAll ()](#apidoc.element.sugar.Object.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>average ()](#apidoc.element.sugar.Object.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>clone ()](#apidoc.element.sugar.Object.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>count ()](#apidoc.element.sugar.Object.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>defaults ()](#apidoc.element.sugar.Object.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>every ()](#apidoc.element.sugar.Object.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>exclude ()](#apidoc.element.sugar.Object.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>filter ()](#apidoc.element.sugar.Object.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>find ()](#apidoc.element.sugar.Object.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>forEach ()](#apidoc.element.sugar.Object.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>get ()](#apidoc.element.sugar.Object.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.Object.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>has ()](#apidoc.element.sugar.Object.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.Object.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>intersect ()](#apidoc.element.sugar.Object.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>invert ()](#apidoc.element.sugar.Object.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isArguments ()](#apidoc.element.sugar.Object.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isArray ()](#apidoc.element.sugar.Object.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isBoolean ()](#apidoc.element.sugar.Object.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isDate ()](#apidoc.element.sugar.Object.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isEmpty ()](#apidoc.element.sugar.Object.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isEqual ()](#apidoc.element.sugar.Object.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isError ()](#apidoc.element.sugar.Object.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isFunction ()](#apidoc.element.sugar.Object.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isMap ()](#apidoc.element.sugar.Object.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isNumber ()](#apidoc.element.sugar.Object.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isObject ()](#apidoc.element.sugar.Object.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.Object.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isRegExp ()](#apidoc.element.sugar.Object.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isSet ()](#apidoc.element.sugar.Object.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>isString ()](#apidoc.element.sugar.Object.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>keys ()](#apidoc.element.sugar.Object.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>least ()](#apidoc.element.sugar.Object.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>map ()](#apidoc.element.sugar.Object.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>max ()](#apidoc.element.sugar.Object.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>median ()](#apidoc.element.sugar.Object.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>merge ()](#apidoc.element.sugar.Object.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>mergeAll ()](#apidoc.element.sugar.Object.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>min ()](#apidoc.element.sugar.Object.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>most ()](#apidoc.element.sugar.Object.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>none ()](#apidoc.element.sugar.Object.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.Object.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>reduce ()](#apidoc.element.sugar.Object.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>reject ()](#apidoc.element.sugar.Object.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>remove ()](#apidoc.element.sugar.Object.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.Object.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>select ()](#apidoc.element.sugar.Object.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>set ()](#apidoc.element.sugar.Object.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.Object.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>size ()](#apidoc.element.sugar.Object.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>some ()](#apidoc.element.sugar.Object.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>subtract ()](#apidoc.element.sugar.Object.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>sum ()](#apidoc.element.sugar.Object.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>tap ()](#apidoc.element.sugar.Object.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>toLocaleString ()](#apidoc.element.sugar.Object.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>toQueryString ()](#apidoc.element.sugar.Object.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.Object.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>toString ()](#apidoc.element.sugar.Object.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.Object.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.Object.prototype.</span>values ()](#apidoc.element.sugar.Object.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.RegExp"></a>[module sugar.RegExp](#apidoc.module.sugar.RegExp)

#### <a name="apidoc.element.sugar.RegExp.RegExp"></a>[function <span class="apidocSignatureSpan">sugar.</span>RegExp {{signature}}](#apidoc.element.sugar.RegExp.RegExp)
- description and source-code
```javascript
SugarRegExp
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.addFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.</span>addFlags (r, flags)](#apidoc.element.sugar.RegExp.addFlags)
- description and source-code
```javascript
addFlags = function (r, flags) {
  return RegExp(r.source, getRegExpFlags(r, flags));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.escape"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.</span>escape (str)](#apidoc.element.sugar.RegExp.escape)
- description and source-code
```javascript
escape = function (str) {
  return escapeRegExp(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.getFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.</span>getFlags (r)](#apidoc.element.sugar.RegExp.getFlags)
- description and source-code
```javascript
getFlags = function (r) {
  return getRegExpFlags(r);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.removeFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.</span>removeFlags (r, flags)](#apidoc.element.sugar.RegExp.removeFlags)
- description and source-code
```javascript
removeFlags = function (r, flags) {
  var reg = allCharsReg(flags);
  return RegExp(r.source, getRegExpFlags(r).replace(reg, ''));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.setFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.</span>setFlags (r, flags)](#apidoc.element.sugar.RegExp.setFlags)
- description and source-code
```javascript
setFlags = function (r, flags) {
  return RegExp(r.source, flags);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.RegExp.prototype"></a>[module sugar.RegExp.prototype](#apidoc.module.sugar.RegExp.prototype)

#### <a name="apidoc.element.sugar.RegExp.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.RegExp.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.RegExp.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.RegExp.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.RegExp.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>add ()](#apidoc.element.sugar.RegExp.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.RegExp.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>addAll ()](#apidoc.element.sugar.RegExp.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.addFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>addFlags ()](#apidoc.element.sugar.RegExp.prototype.addFlags)
- description and source-code
```javascript
addFlags = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>average ()](#apidoc.element.sugar.RegExp.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>clone ()](#apidoc.element.sugar.RegExp.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.compile"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>compile ()](#apidoc.element.sugar.RegExp.prototype.compile)
- description and source-code
```javascript
compile = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>count ()](#apidoc.element.sugar.RegExp.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>defaults ()](#apidoc.element.sugar.RegExp.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>every ()](#apidoc.element.sugar.RegExp.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>exclude ()](#apidoc.element.sugar.RegExp.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.exec"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>exec ()](#apidoc.element.sugar.RegExp.prototype.exec)
- description and source-code
```javascript
exec = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>filter ()](#apidoc.element.sugar.RegExp.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>find ()](#apidoc.element.sugar.RegExp.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>forEach ()](#apidoc.element.sugar.RegExp.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>get ()](#apidoc.element.sugar.RegExp.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.RegExp.prototype.getFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>getFlags ()](#apidoc.element.sugar.RegExp.prototype.getFlags)
- description and source-code
```javascript
getFlags = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>has ()](#apidoc.element.sugar.RegExp.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.RegExp.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>intersect ()](#apidoc.element.sugar.RegExp.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>invert ()](#apidoc.element.sugar.RegExp.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isArguments ()](#apidoc.element.sugar.RegExp.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isArray ()](#apidoc.element.sugar.RegExp.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isBoolean ()](#apidoc.element.sugar.RegExp.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isDate ()](#apidoc.element.sugar.RegExp.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isEmpty ()](#apidoc.element.sugar.RegExp.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isEqual ()](#apidoc.element.sugar.RegExp.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isError ()](#apidoc.element.sugar.RegExp.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isFunction ()](#apidoc.element.sugar.RegExp.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isMap ()](#apidoc.element.sugar.RegExp.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isNumber ()](#apidoc.element.sugar.RegExp.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isObject ()](#apidoc.element.sugar.RegExp.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.RegExp.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isRegExp ()](#apidoc.element.sugar.RegExp.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isSet ()](#apidoc.element.sugar.RegExp.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>isString ()](#apidoc.element.sugar.RegExp.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>keys ()](#apidoc.element.sugar.RegExp.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>least ()](#apidoc.element.sugar.RegExp.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>map ()](#apidoc.element.sugar.RegExp.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>max ()](#apidoc.element.sugar.RegExp.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>median ()](#apidoc.element.sugar.RegExp.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>merge ()](#apidoc.element.sugar.RegExp.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>mergeAll ()](#apidoc.element.sugar.RegExp.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>min ()](#apidoc.element.sugar.RegExp.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>most ()](#apidoc.element.sugar.RegExp.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>none ()](#apidoc.element.sugar.RegExp.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.RegExp.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>reduce ()](#apidoc.element.sugar.RegExp.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>reject ()](#apidoc.element.sugar.RegExp.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>remove ()](#apidoc.element.sugar.RegExp.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.RegExp.prototype.removeFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>removeFlags ()](#apidoc.element.sugar.RegExp.prototype.removeFlags)
- description and source-code
```javascript
removeFlags = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>select ()](#apidoc.element.sugar.RegExp.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>set ()](#apidoc.element.sugar.RegExp.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.RegExp.prototype.setFlags"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>setFlags ()](#apidoc.element.sugar.RegExp.prototype.setFlags)
- description and source-code
```javascript
setFlags = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>size ()](#apidoc.element.sugar.RegExp.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>some ()](#apidoc.element.sugar.RegExp.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>subtract ()](#apidoc.element.sugar.RegExp.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>sum ()](#apidoc.element.sugar.RegExp.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>tap ()](#apidoc.element.sugar.RegExp.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.test"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>test ()](#apidoc.element.sugar.RegExp.prototype.test)
- description and source-code
```javascript
test = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>toLocaleString ()](#apidoc.element.sugar.RegExp.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>toQueryString ()](#apidoc.element.sugar.RegExp.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.RegExp.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>toString ()](#apidoc.element.sugar.RegExp.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.RegExp.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.RegExp.prototype.</span>values ()](#apidoc.element.sugar.RegExp.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.String"></a>[module sugar.String](#apidoc.module.sugar.String)

#### <a name="apidoc.element.sugar.String.String"></a>[function <span class="apidocSignatureSpan">sugar.</span>String {{signature}}](#apidoc.element.sugar.String.String)
- description and source-code
```javascript
SugarString
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.at"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>at (str, index, loop)](#apidoc.element.sugar.String.at)
- description and source-code
```javascript
at = function (str, index, loop) {
  return getEntriesForIndexes(str, index, loop, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.camelize"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>camelize (str, upper)](#apidoc.element.sugar.String.camelize)
- description and source-code
```javascript
camelize = function (str, upper) {
  return stringCamelize(str, upper);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.capitalize"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>capitalize (str, lower, all)](#apidoc.element.sugar.String.capitalize)
- description and source-code
```javascript
capitalize = function (str, lower, all) {
  return stringCapitalize(str, lower, all);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.chars"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>chars (str, search, fn)](#apidoc.element.sugar.String.chars)
- description and source-code
```javascript
chars = function (str, search, fn) {
  return stringEach(str, search, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.codes"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>codes (str, fn)](#apidoc.element.sugar.String.codes)
- description and source-code
```javascript
codes = function (str, fn) {
  return stringCodes(str, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.compact"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>compact (str)](#apidoc.element.sugar.String.compact)
- description and source-code
```javascript
compact = function (str) {
  return trim(str).replace(/([\r\n\s　])+/g, function(match, whitespace) {
    return whitespace === '　' ? whitespace : ' ';
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.dasherize"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>dasherize (str)](#apidoc.element.sugar.String.dasherize)
- description and source-code
```javascript
dasherize = function (str) {
  return stringUnderscore(str).replace(/_/g, '-');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.decodeBase64"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>decodeBase64 (str)](#apidoc.element.sugar.String.decodeBase64)
- description and source-code
```javascript
decodeBase64 = function (str) {
  return decodeBase64(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.encodeBase64"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>encodeBase64 (str)](#apidoc.element.sugar.String.encodeBase64)
- description and source-code
```javascript
encodeBase64 = function (str) {
  return encodeBase64(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.escapeHTML"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>escapeHTML (str)](#apidoc.element.sugar.String.escapeHTML)
- description and source-code
```javascript
escapeHTML = function (str) {
  return str.replace(HTML_ESCAPE_REG, function(chr) {
    return getOwn(HTMLToEntityMap, chr);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.escapeURL"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>escapeURL (str, param)](#apidoc.element.sugar.String.escapeURL)
- description and source-code
```javascript
escapeURL = function (str, param) {
  return param ? encodeURIComponent(str) : encodeURI(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.first"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>first (str, num)](#apidoc.element.sugar.String.first)
- description and source-code
```javascript
first = function (str, num) {
  if (isUndefined(num)) num = 1;
  return str.substr(0, num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.forEach"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>forEach (str, search, fn)](#apidoc.element.sugar.String.forEach)
- description and source-code
```javascript
forEach = function (str, search, fn) {
  return stringEach(str, search, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.format"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>format ()](#apidoc.element.sugar.String.format)
- description and source-code
```javascript
format = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.from"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>from (str, from)](#apidoc.element.sugar.String.from)
- description and source-code
```javascript
from = function (str, from) {
  return str.slice(numberOrIndex(str, from, true));
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
    coercePositiveInteger = require('../common/internal/coercePositiveInteger');

Sugar.Array.defineStatic({

  'construct': function(n, fn) {
    n = coercePositiveInteger(n);
    return Array.from(new Array(n), function(el, i) {
      return fn && fn(i);
    });
  }

});

module.exports = Sugar.Array.construct;
...
```

#### <a name="apidoc.element.sugar.String.includes"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>includes (a)](#apidoc.element.sugar.String.includes)
- description and source-code
```javascript
includes = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.insert"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>insert (str, substr, index)](#apidoc.element.sugar.String.insert)
- description and source-code
```javascript
insert = function (str, substr, index) {
  index = isUndefined(index) ? str.length : index;
  return str.slice(0, index) + substr + str.slice(index);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.isBlank"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>isBlank (str)](#apidoc.element.sugar.String.isBlank)
- description and source-code
```javascript
isBlank = function (str) {
  return trim(str).length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>isEmpty (str)](#apidoc.element.sugar.String.isEmpty)
- description and source-code
```javascript
isEmpty = function (str) {
  return str.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.last"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>last (str, num)](#apidoc.element.sugar.String.last)
- description and source-code
```javascript
last = function (str, num) {
  if (isUndefined(num)) num = 1;
  var start = str.length - num < 0 ? 0 : str.length - num;
  return str.substr(start);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.lines"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>lines (str, fn)](#apidoc.element.sugar.String.lines)
- description and source-code
```javascript
lines = function (str, fn) {
  return stringEach(trim(str), /^.*$/gm, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.pad"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>pad (str, num, padding)](#apidoc.element.sugar.String.pad)
- description and source-code
```javascript
pad = function (str, num, padding) {
  var half, front, back;
  num   = coercePositiveInteger(num);
  half  = max(0, num - str.length) / 2;
  front = floor(half);
  back  = ceil(half);
  return padString(front, padding) + str + padString(back, padding);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.padLeft"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>padLeft (str, num, padding)](#apidoc.element.sugar.String.padLeft)
- description and source-code
```javascript
padLeft = function (str, num, padding) {
  num = coercePositiveInteger(num);
  return padString(max(0, num - str.length), padding) + str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.padRight"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>padRight (str, num, padding)](#apidoc.element.sugar.String.padRight)
- description and source-code
```javascript
padRight = function (str, num, padding) {
  num = coercePositiveInteger(num);
  return str + padString(max(0, num - str.length), padding);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.parameterize"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>parameterize (str, separator)](#apidoc.element.sugar.String.parameterize)
- description and source-code
```javascript
parameterize = function (str, separator) {
  return stringParameterize(str, separator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.range"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>range (start, end)](#apidoc.element.sugar.String.range)
- description and source-code
```javascript
range = function (start, end) {
  return new Range(start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.remove"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>remove (str, f)](#apidoc.element.sugar.String.remove)
- description and source-code
```javascript
remove = function (str, f) {
  return str.replace(f, '');
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.String.removeAll"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>removeAll (str, f)](#apidoc.element.sugar.String.removeAll)
- description and source-code
```javascript
removeAll = function (str, f) {
  return stringReplaceAll(str, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.removeTags"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>removeTags (str, tag, replace)](#apidoc.element.sugar.String.removeTags)
- description and source-code
```javascript
removeTags = function (str, tag, replace) {
  return replaceTags(str, tag, replace, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.replaceAll"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>replaceAll ()](#apidoc.element.sugar.String.replaceAll)
- description and source-code
```javascript
replaceAll = function () {
  var args = [], collectedArgs = [], len;
  if (instance) {
    args.push(this);
  }
  len = Math.max(arguments.length, startCollect);
  // Optimized: no leaking arguments
  for (var i = 0; i < len; i++) {
    if (i < startCollect) {
      args.push(arguments[i]);
    } else {
      collectedArgs.push(arguments[i]);
    }
  }
  args.push(collectedArgs);
  return fn.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.reverse"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>reverse (str)](#apidoc.element.sugar.String.reverse)
- description and source-code
```javascript
reverse = function (str) {
  return reverseString(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.shift"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>shift (str, n)](#apidoc.element.sugar.String.shift)
- description and source-code
```javascript
shift = function (str, n) {
  var result = '';
  n = n || 0;
  stringCodes(str, function(c) {
    result += chr(c + n);
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.spacify"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>spacify (str)](#apidoc.element.sugar.String.spacify)
- description and source-code
```javascript
spacify = function (str) {
  return stringSpacify(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.stripTags"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>stripTags (str, tag, replace)](#apidoc.element.sugar.String.stripTags)
- description and source-code
```javascript
stripTags = function (str, tag, replace) {
  return replaceTags(str, tag, replace, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.titleize"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>titleize (str)](#apidoc.element.sugar.String.titleize)
- description and source-code
```javascript
titleize = function (str) {
  return stringTitleize(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.to"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>to (str, to)](#apidoc.element.sugar.String.to)
- description and source-code
```javascript
to = function (str, to) {
  if (isUndefined(to)) to = str.length;
  return str.slice(0, numberOrIndex(str, to));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.toNumber"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>toNumber (str, base)](#apidoc.element.sugar.String.toNumber)
- description and source-code
```javascript
toNumber = function (str, base) {
  return stringToNumber(str, base);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.trimLeft"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>trimLeft (str)](#apidoc.element.sugar.String.trimLeft)
- description and source-code
```javascript
trimLeft = function (str) {
  return str.replace(LEFT_TRIM_REG, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.trimRight"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>trimRight (str)](#apidoc.element.sugar.String.trimRight)
- description and source-code
```javascript
trimRight = function (str) {
  return str.replace(RIGHT_TRIM_REG, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.truncate"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>truncate (str, length, from, ellipsis)](#apidoc.element.sugar.String.truncate)
- description and source-code
```javascript
truncate = function (str, length, from, ellipsis) {
  return truncateString(str, length, from, ellipsis);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.truncateOnWord"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>truncateOnWord (str, length, from, ellipsis)](#apidoc.element.sugar.String.truncateOnWord)
- description and source-code
```javascript
truncateOnWord = function (str, length, from, ellipsis) {
  return truncateString(str, length, from, ellipsis, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.underscore"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>underscore (str)](#apidoc.element.sugar.String.underscore)
- description and source-code
```javascript
underscore = function (str) {
  return stringUnderscore(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.unescapeHTML"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>unescapeHTML (str)](#apidoc.element.sugar.String.unescapeHTML)
- description and source-code
```javascript
unescapeHTML = function (str) {
  return unescapeHTML(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.unescapeURL"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>unescapeURL (str, param)](#apidoc.element.sugar.String.unescapeURL)
- description and source-code
```javascript
unescapeURL = function (str, param) {
  return param ? decodeURI(str) : decodeURIComponent(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.words"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>words (str, fn)](#apidoc.element.sugar.String.words)
- description and source-code
```javascript
words = function (str, fn) {
  return stringEach(trim(str), /\S+/g, fn);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.String.includes"></a>[module sugar.String.includes](#apidoc.module.sugar.String.includes)

#### <a name="apidoc.element.sugar.String.includes.includes"></a>[function <span class="apidocSignatureSpan">sugar.String.</span>includes (a)](#apidoc.element.sugar.String.includes.includes)
- description and source-code
```javascript
includes = function (a) {
  var args = arguments;
  return fn(a, args[1], args[2], args.length - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.includes.instance"></a>[function <span class="apidocSignatureSpan">sugar.String.includes.</span>instance (b)](#apidoc.element.sugar.String.includes.instance)
- description and source-code
```javascript
instance = function (b) {
  var args = arguments;
  return fn(this, b, args[1], args.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sugar.String.prototype"></a>[module sugar.String.prototype](#apidoc.module.sugar.String.prototype)

#### <a name="apidoc.element.sugar.String.prototype.__defineGetter__"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__defineGetter__ ()](#apidoc.element.sugar.String.prototype.__defineGetter__)
- description and source-code
```javascript
__defineGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.__defineSetter__"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__defineSetter__ ()](#apidoc.element.sugar.String.prototype.__defineSetter__)
- description and source-code
```javascript
__defineSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.__lookupGetter__"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__lookupGetter__ ()](#apidoc.element.sugar.String.prototype.__lookupGetter__)
- description and source-code
```javascript
__lookupGetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.__lookupSetter__"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>__lookupSetter__ ()](#apidoc.element.sugar.String.prototype.__lookupSetter__)
- description and source-code
```javascript
__lookupSetter__ = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.add"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>add ()](#apidoc.element.sugar.String.prototype.add)
- description and source-code
```javascript
add = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'addLocale': function(code, set) {
    return localeManager.add(code, set);
  }

});

module.exports = Sugar.Date.addLocale;
...
```

#### <a name="apidoc.element.sugar.String.prototype.addAll"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>addAll ()](#apidoc.element.sugar.String.prototype.addAll)
- description and source-code
```javascript
addAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.anchor"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>anchor ()](#apidoc.element.sugar.String.prototype.anchor)
- description and source-code
```javascript
anchor = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.at"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>at ()](#apidoc.element.sugar.String.prototype.at)
- description and source-code
```javascript
at = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.average"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>average ()](#apidoc.element.sugar.String.prototype.average)
- description and source-code
```javascript
average = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.big"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>big ()](#apidoc.element.sugar.String.prototype.big)
- description and source-code
```javascript
big = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.blink"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>blink ()](#apidoc.element.sugar.String.prototype.blink)
- description and source-code
```javascript
blink = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.bold"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>bold ()](#apidoc.element.sugar.String.prototype.bold)
- description and source-code
```javascript
bold = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.camelize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>camelize ()](#apidoc.element.sugar.String.prototype.camelize)
- description and source-code
```javascript
camelize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.capitalize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>capitalize ()](#apidoc.element.sugar.String.prototype.capitalize)
- description and source-code
```javascript
capitalize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.charAt"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>charAt ()](#apidoc.element.sugar.String.prototype.charAt)
- description and source-code
```javascript
charAt = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.charCodeAt"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>charCodeAt ()](#apidoc.element.sugar.String.prototype.charCodeAt)
- description and source-code
```javascript
charCodeAt = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.chars"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>chars ()](#apidoc.element.sugar.String.prototype.chars)
- description and source-code
```javascript
chars = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.clone"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>clone ()](#apidoc.element.sugar.String.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.codePointAt"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>codePointAt ()](#apidoc.element.sugar.String.prototype.codePointAt)
- description and source-code
```javascript
codePointAt = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.codes"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>codes ()](#apidoc.element.sugar.String.prototype.codes)
- description and source-code
```javascript
codes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.compact"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>compact ()](#apidoc.element.sugar.String.prototype.compact)
- description and source-code
```javascript
compact = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.concat"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>concat ()](#apidoc.element.sugar.String.prototype.concat)
- description and source-code
```javascript
concat = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
    map = require('../common/internal/map');

Sugar.Array.defineInstanceWithArguments({

  'zip': function(arr, args) {
    return map(arr, function(el, i) {
      return [el].concat(map(args, function(k) {
        return (i in k) ? k[i] : null;
      }));
    });
  }

});
...
```

#### <a name="apidoc.element.sugar.String.prototype.count"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>count ()](#apidoc.element.sugar.String.prototype.count)
- description and source-code
```javascript
count = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.dasherize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>dasherize ()](#apidoc.element.sugar.String.prototype.dasherize)
- description and source-code
```javascript
dasherize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.decodeBase64"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>decodeBase64 ()](#apidoc.element.sugar.String.prototype.decodeBase64)
- description and source-code
```javascript
decodeBase64 = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.defaults"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>defaults ()](#apidoc.element.sugar.String.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.encodeBase64"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>encodeBase64 ()](#apidoc.element.sugar.String.prototype.encodeBase64)
- description and source-code
```javascript
encodeBase64 = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.endsWith"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>endsWith ()](#apidoc.element.sugar.String.prototype.endsWith)
- description and source-code
```javascript
endsWith = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.entityify"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>entityify ()](#apidoc.element.sugar.String.prototype.entityify)
- description and source-code
```javascript
entityify = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.escapeHTML"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>escapeHTML ()](#apidoc.element.sugar.String.prototype.escapeHTML)
- description and source-code
```javascript
escapeHTML = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.escapeURL"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>escapeURL ()](#apidoc.element.sugar.String.prototype.escapeURL)
- description and source-code
```javascript
escapeURL = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.every"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>every ()](#apidoc.element.sugar.String.prototype.every)
- description and source-code
```javascript
every = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.exclude"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>exclude ()](#apidoc.element.sugar.String.prototype.exclude)
- description and source-code
```javascript
exclude = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.filter"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>filter ()](#apidoc.element.sugar.String.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.find"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>find ()](#apidoc.element.sugar.String.prototype.find)
- description and source-code
```javascript
find = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.first"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>first ()](#apidoc.element.sugar.String.prototype.first)
- description and source-code
```javascript
first = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.fixed"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>fixed ()](#apidoc.element.sugar.String.prototype.fixed)
- description and source-code
```javascript
fixed = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.fontcolor"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>fontcolor ()](#apidoc.element.sugar.String.prototype.fontcolor)
- description and source-code
```javascript
fontcolor = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.fontsize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>fontsize ()](#apidoc.element.sugar.String.prototype.fontsize)
- description and source-code
```javascript
fontsize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.forEach"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>forEach ()](#apidoc.element.sugar.String.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.format"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>format ()](#apidoc.element.sugar.String.prototype.format)
- description and source-code
```javascript
format = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.from"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>from ()](#apidoc.element.sugar.String.prototype.from)
- description and source-code
```javascript
from = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
var Sugar = require('sugar-core'),
    coercePositiveInteger = require('../common/internal/coercePositiveInteger');

Sugar.Array.defineStatic({

  'construct': function(n, fn) {
    n = coercePositiveInteger(n);
    return Array.from(new Array(n), function(el, i) {
      return fn && fn(i);
    });
  }

});

module.exports = Sugar.Array.construct;
...
```

#### <a name="apidoc.element.sugar.String.prototype.get"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>get ()](#apidoc.element.sugar.String.prototype.get)
- description and source-code
```javascript
get = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'getLocale': function(code) {
    return localeManager.get(code, !code);
  }

});

module.exports = Sugar.Date.getLocale;
...
```

#### <a name="apidoc.element.sugar.String.prototype.has"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>has ()](#apidoc.element.sugar.String.prototype.has)
- description and source-code
```javascript
has = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.hasOwnProperty"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>hasOwnProperty ()](#apidoc.element.sugar.String.prototype.hasOwnProperty)
- description and source-code
```javascript
hasOwnProperty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.includes"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>includes ()](#apidoc.element.sugar.String.prototype.includes)
- description and source-code
```javascript
includes = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>indexOf ()](#apidoc.element.sugar.String.prototype.indexOf)
- description and source-code
```javascript
indexOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.insert"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>insert ()](#apidoc.element.sugar.String.prototype.insert)
- description and source-code
```javascript
insert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.intersect"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>intersect ()](#apidoc.element.sugar.String.prototype.intersect)
- description and source-code
```javascript
intersect = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.invert"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>invert ()](#apidoc.element.sugar.String.prototype.invert)
- description and source-code
```javascript
invert = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isAlpha"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isAlpha ()](#apidoc.element.sugar.String.prototype.isAlpha)
- description and source-code
```javascript
isAlpha = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isArguments ()](#apidoc.element.sugar.String.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isArray"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isArray ()](#apidoc.element.sugar.String.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isBlank"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isBlank ()](#apidoc.element.sugar.String.prototype.isBlank)
- description and source-code
```javascript
isBlank = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isBoolean ()](#apidoc.element.sugar.String.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isDate"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isDate ()](#apidoc.element.sugar.String.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isDigit"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isDigit ()](#apidoc.element.sugar.String.prototype.isDigit)
- description and source-code
```javascript
isDigit = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isEmpty ()](#apidoc.element.sugar.String.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isEqual ()](#apidoc.element.sugar.String.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isError"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isError ()](#apidoc.element.sugar.String.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isFunction ()](#apidoc.element.sugar.String.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isMap"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isMap ()](#apidoc.element.sugar.String.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isNumber ()](#apidoc.element.sugar.String.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isObject"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isObject ()](#apidoc.element.sugar.String.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isPrototypeOf"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isPrototypeOf ()](#apidoc.element.sugar.String.prototype.isPrototypeOf)
- description and source-code
```javascript
isPrototypeOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isRegExp ()](#apidoc.element.sugar.String.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isSet"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isSet ()](#apidoc.element.sugar.String.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.isString"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>isString ()](#apidoc.element.sugar.String.prototype.isString)
- description and source-code
```javascript
isString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.italics"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>italics ()](#apidoc.element.sugar.String.prototype.italics)
- description and source-code
```javascript
italics = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.keys"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>keys ()](#apidoc.element.sugar.String.prototype.keys)
- description and source-code
```javascript
keys = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.last"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>last ()](#apidoc.element.sugar.String.prototype.last)
- description and source-code
```javascript
last = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.lastIndexOf"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>lastIndexOf ()](#apidoc.element.sugar.String.prototype.lastIndexOf)
- description and source-code
```javascript
lastIndexOf = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.least"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>least ()](#apidoc.element.sugar.String.prototype.least)
- description and source-code
```javascript
least = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.lines"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>lines ()](#apidoc.element.sugar.String.prototype.lines)
- description and source-code
```javascript
lines = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.link"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>link ()](#apidoc.element.sugar.String.prototype.link)
- description and source-code
```javascript
link = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.localeCompare"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>localeCompare ()](#apidoc.element.sugar.String.prototype.localeCompare)
- description and source-code
```javascript
localeCompare = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.map"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>map ()](#apidoc.element.sugar.String.prototype.map)
- description and source-code
```javascript
map = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.match"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>match ()](#apidoc.element.sugar.String.prototype.match)
- description and source-code
```javascript
match = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.max"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>max ()](#apidoc.element.sugar.String.prototype.max)
- description and source-code
```javascript
max = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.median"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>median ()](#apidoc.element.sugar.String.prototype.median)
- description and source-code
```javascript
median = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.merge"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>merge ()](#apidoc.element.sugar.String.prototype.merge)
- description and source-code
```javascript
merge = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>mergeAll ()](#apidoc.element.sugar.String.prototype.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.min"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>min ()](#apidoc.element.sugar.String.prototype.min)
- description and source-code
```javascript
min = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.most"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>most ()](#apidoc.element.sugar.String.prototype.most)
- description and source-code
```javascript
most = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.none"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>none ()](#apidoc.element.sugar.String.prototype.none)
- description and source-code
```javascript
none = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.normalize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>normalize ()](#apidoc.element.sugar.String.prototype.normalize)
- description and source-code
```javascript
normalize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.pad"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>pad ()](#apidoc.element.sugar.String.prototype.pad)
- description and source-code
```javascript
pad = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.padLeft"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>padLeft ()](#apidoc.element.sugar.String.prototype.padLeft)
- description and source-code
```javascript
padLeft = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.padRight"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>padRight ()](#apidoc.element.sugar.String.prototype.padRight)
- description and source-code
```javascript
padRight = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.parameterize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>parameterize ()](#apidoc.element.sugar.String.prototype.parameterize)
- description and source-code
```javascript
parameterize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.propertyIsEnumerable"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>propertyIsEnumerable ()](#apidoc.element.sugar.String.prototype.propertyIsEnumerable)
- description and source-code
```javascript
propertyIsEnumerable = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.reduce"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>reduce ()](#apidoc.element.sugar.String.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.reject"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>reject ()](#apidoc.element.sugar.String.prototype.reject)
- description and source-code
```javascript
reject = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.remove"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>remove ()](#apidoc.element.sugar.String.prototype.remove)
- description and source-code
```javascript
remove = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'removeLocale': function(code) {
    return localeManager.remove(code);
  }

});

module.exports = Sugar.Date.removeLocale;
...
```

#### <a name="apidoc.element.sugar.String.prototype.removeAll"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>removeAll ()](#apidoc.element.sugar.String.prototype.removeAll)
- description and source-code
```javascript
removeAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.removeTags"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>removeTags ()](#apidoc.element.sugar.String.prototype.removeTags)
- description and source-code
```javascript
removeTags = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.repeat"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>repeat ()](#apidoc.element.sugar.String.prototype.repeat)
- description and source-code
```javascript
repeat = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.replace"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>replace ()](#apidoc.element.sugar.String.prototype.replace)
- description and source-code
```javascript
replace = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
}
var text = this['units'][(mult * 8) + unit];
var prefix = num + ' ';

// changing to accusative case for 'past' and 'future' formats
// (only singular feminine unit words are different in accusative, each of which ends with 'a')
if ((format === 'past' || format === 'future') && num === 1) {
  text = text.replace(/a$/, 'ę');
}

text = prefix + text;
switch (format) {
  case 'duration': return text;
  case 'past':     return text + ' temu';
  case 'future':   return 'za ' + text;
...
```

#### <a name="apidoc.element.sugar.String.prototype.replaceAll"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>replaceAll ()](#apidoc.element.sugar.String.prototype.replaceAll)
- description and source-code
```javascript
replaceAll = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.reverse"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>reverse ()](#apidoc.element.sugar.String.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.search"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>search ()](#apidoc.element.sugar.String.prototype.search)
- description and source-code
```javascript
search = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.select"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>select ()](#apidoc.element.sugar.String.prototype.select)
- description and source-code
```javascript
select = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.set"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>set ()](#apidoc.element.sugar.String.prototype.set)
- description and source-code
```javascript
set = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    LocaleHelpers = require('./var/LocaleHelpers');

var localeManager = LocaleHelpers.localeManager;

Sugar.Date.defineStatic({

  'setLocale': function(code) {
    return localeManager.set(code);
  }

});

module.exports = Sugar.Date.setLocale;
...
```

#### <a name="apidoc.element.sugar.String.prototype.shift"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>shift ()](#apidoc.element.sugar.String.prototype.shift)
- description and source-code
```javascript
shift = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.size"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>size ()](#apidoc.element.sugar.String.prototype.size)
- description and source-code
```javascript
size = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.slice"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>slice ()](#apidoc.element.sugar.String.prototype.slice)
- description and source-code
```javascript
slice = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
    isUndefined = require('../common/internal/isUndefined');

Sugar.Array.defineInstance({

  'first': function(arr, num) {
    if (isUndefined(num)) return arr[0];
    if (num < 0) num = 0;
    return arr.slice(0, num);
  }

});

module.exports = Sugar.Array.first;
...
```

#### <a name="apidoc.element.sugar.String.prototype.small"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>small ()](#apidoc.element.sugar.String.prototype.small)
- description and source-code
```javascript
small = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.some"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>some ()](#apidoc.element.sugar.String.prototype.some)
- description and source-code
```javascript
some = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.spacify"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>spacify ()](#apidoc.element.sugar.String.prototype.spacify)
- description and source-code
```javascript
spacify = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.split"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>split ()](#apidoc.element.sugar.String.prototype.split)
- description and source-code
```javascript
split = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.startsWith"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>startsWith ()](#apidoc.element.sugar.String.prototype.startsWith)
- description and source-code
```javascript
startsWith = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.strike"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>strike ()](#apidoc.element.sugar.String.prototype.strike)
- description and source-code
```javascript
strike = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.stripTags"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>stripTags ()](#apidoc.element.sugar.String.prototype.stripTags)
- description and source-code
```javascript
stripTags = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.sub"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>sub ()](#apidoc.element.sugar.String.prototype.sub)
- description and source-code
```javascript
sub = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.substr"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>substr ()](#apidoc.element.sugar.String.prototype.substr)
- description and source-code
```javascript
substr = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.substring"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>substring ()](#apidoc.element.sugar.String.prototype.substring)
- description and source-code
```javascript
substring = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.subtract"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>subtract ()](#apidoc.element.sugar.String.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.sum"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>sum ()](#apidoc.element.sugar.String.prototype.sum)
- description and source-code
```javascript
sum = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.sup"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>sup ()](#apidoc.element.sugar.String.prototype.sup)
- description and source-code
```javascript
sup = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.supplant"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>supplant ()](#apidoc.element.sugar.String.prototype.supplant)
- description and source-code
```javascript
supplant = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.tap"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>tap ()](#apidoc.element.sugar.String.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.titleize"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>titleize ()](#apidoc.element.sugar.String.prototype.titleize)
- description and source-code
```javascript
titleize = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.to"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>to ()](#apidoc.element.sugar.String.prototype.to)
- description and source-code
```javascript
to = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toLocaleLowerCase"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLocaleLowerCase ()](#apidoc.element.sugar.String.prototype.toLocaleLowerCase)
- description and source-code
```javascript
toLocaleLowerCase = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toLocaleString"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLocaleString ()](#apidoc.element.sugar.String.prototype.toLocaleString)
- description and source-code
```javascript
toLocaleString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toLocaleUpperCase"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLocaleUpperCase ()](#apidoc.element.sugar.String.prototype.toLocaleUpperCase)
- description and source-code
```javascript
toLocaleUpperCase = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toLowerCase"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toLowerCase ()](#apidoc.element.sugar.String.prototype.toLowerCase)
- description and source-code
```javascript
toLowerCase = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toNumber ()](#apidoc.element.sugar.String.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toQueryString"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toQueryString ()](#apidoc.element.sugar.String.prototype.toQueryString)
- description and source-code
```javascript
toQueryString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.toString"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toString ()](#apidoc.element.sugar.String.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
...
  { 'name': 'day', 'src': 'послезавтра', 'value': 2 },
  { 'name': 'sign', 'src': 'назад', 'value': -1 },
  { 'name': 'sign', 'src': 'через', 'value': 1 },
  { 'name': 'shift', 'src': 'прошл:ый|ой|ом', 'value': -1 },
  { 'name': 'shift', 'src': 'следующ:ий|ей|ем', 'value': 1 }
],
'relative': function(num, unit, ms, format) {
  var numberWithUnit, last = num.toString().slice(-1), mult;
  switch(true) {
    case num >= 11 && num <= 15: mult = 3; break;
    case last == 1: mult = 1; break;
    case last >= 2 && last <= 4: mult = 2; break;
    default: mult = 3;
  }
  numberWithUnit = num + ' ' + this['units'][(mult * 8) + unit];
...
```

#### <a name="apidoc.element.sugar.String.prototype.toUpperCase"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>toUpperCase ()](#apidoc.element.sugar.String.prototype.toUpperCase)
- description and source-code
```javascript
toUpperCase = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.trim"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>trim ()](#apidoc.element.sugar.String.prototype.trim)
- description and source-code
```javascript
trim = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.trimLeft"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>trimLeft ()](#apidoc.element.sugar.String.prototype.trimLeft)
- description and source-code
```javascript
trimLeft = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.trimRight"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>trimRight ()](#apidoc.element.sugar.String.prototype.trimRight)
- description and source-code
```javascript
trimRight = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.truncate"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>truncate ()](#apidoc.element.sugar.String.prototype.truncate)
- description and source-code
```javascript
truncate = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.truncateOnWord"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>truncateOnWord ()](#apidoc.element.sugar.String.prototype.truncateOnWord)
- description and source-code
```javascript
truncateOnWord = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.underscore"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>underscore ()](#apidoc.element.sugar.String.prototype.underscore)
- description and source-code
```javascript
underscore = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.unescapeHTML"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>unescapeHTML ()](#apidoc.element.sugar.String.prototype.unescapeHTML)
- description and source-code
```javascript
unescapeHTML = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.unescapeURL"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>unescapeURL ()](#apidoc.element.sugar.String.prototype.unescapeURL)
- description and source-code
```javascript
unescapeURL = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.values"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>values ()](#apidoc.element.sugar.String.prototype.values)
- description and source-code
```javascript
values = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sugar.String.prototype.words"></a>[function <span class="apidocSignatureSpan">sugar.String.prototype.</span>words ()](#apidoc.element.sugar.String.prototype.words)
- description and source-code
```javascript
words = function () {
  return new DefaultChainable(fn.apply(this.raw, arguments));
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
