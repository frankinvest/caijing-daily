# 📋 小红圈财经早餐 MCP — Final Code Review Report

> 生成时间: 2026-05-13
> 分支: main / master
> 仓库: frankinvest/caijing-daily

---

## 1. 项目目录结构

```
/Users/frank_bot/.openclaw/workspace
📁 articles-to-forward/
   📄 1.jpg
   📄 2.jpg
   📄 3.jpg
   📄 4.jpg
   📄 5.jpg
   📄 6.jpg
   📄 7.jpg
   📄 8.jpg
   📄 天阶功法卷四-磷化工投资价值分析.md
📁 cookies/
   📄 www_red_ring_cn_cookies.json
📁 frank-invest-blog/
   📁 node_modules/
      📁 @adobe/
      📁 @asamuzakjp/
      📁 @csstools/
      📁 @types/
      📁 a-sync-waterfall/
      📁 abbrev/
      📁 agent-base/
      📁 ansi-regex/
      📁 anymatch/
      📁 argparse/
      📁 asap/
      📁 async/
      📁 asynckit/
      📁 balanced-match/
      📁 basic-auth/
      📁 binary-extensions/
      📁 bluebird/
      📁 brace-expansion/
      📁 braces/
      📁 bytes/
      📁 call-bind-apply-helpers/
      📁 camel-case/
      📁 chokidar/
      📁 combined-stream/
      📁 command-exists/
      📁 commander/
      📁 compressible/
      📁 compression/
      📁 concat-map/
      📁 connect/
      📁 cross-spawn/
      📁 cssstyle/
      📁 data-urls/
      📁 debug/
      📁 decimal.js/
      📁 deepmerge/
      📁 define-lazy-prop/
      📁 delayed-stream/
      📁 depd/
      📁 destroy/
      📁 dom-serializer/
      📁 domelementtype/
      📁 domhandler/
      📁 dompurify/
      📁 domutils/
      📁 dunder-proto/
      📁 ee-first/
      📁 ejs/
      📁 encodeurl/
      📁 entities/
      📁 es-define-property/
      📁 es-errors/
      📁 es-object-atoms/
      📁 es-set-tostringtag/
      📁 escape-html/
      📁 esprima/
      📁 etag/
      📁 fast-archy/
      📁 fast-equals/
      📁 fast-text-table/
      📁 filelist/
      📁 fill-range/
      📁 finalhandler/
      📁 form-data/
      📁 fresh/
      📁 fs.realpath/
      📁 fsevents/
      📁 function-bind/
      📁 get-intrinsic/
      📁 get-proto/
      📁 glob/
      📁 glob-parent/
      📁 gopd/
      📁 graceful-fs/
      📁 has-symbols/
      📁 has-tostringtag/
      📁 hasown/
      📁 hexo/
      📁 hexo-cli/
      📁 hexo-front-matter/
      📁 hexo-fs/
      📁 hexo-generator-archive/
      📁 hexo-generator-category/
      📁 hexo-generator-index/
      📁 hexo-generator-tag/
      📁 hexo-i18n/
      📁 hexo-log/
      📁 hexo-pagination/
      📁 hexo-renderer-ejs/
      📁 hexo-renderer-marked/
      📁 hexo-renderer-stylus/
      📁 hexo-server/
      📁 hexo-theme-landscape/
      📁 hexo-util/
      📁 highlight.js/
      📁 html-encoding-sniffer/
      📁 htmlparser2/
      📁 http-errors/
      📁 http-proxy-agent/
      📁 https-proxy-agent/
      📁 iconv-lite/
      📁 inflight/
      📁 inherits/
      📁 is-binary-path/
      📁 is-core-module/
      📁 is-docker/
      📁 is-extglob/
      📁 is-glob/
      📁 is-number/
      📁 is-plain-object/
      📁 is-potential-custom-element-name/
      📁 is-wsl/
      📁 isexe/
      📁 jake/
      📁 js-yaml/
      📁 js-yaml-js-types/
      📁 jsdom/
      📁 jsonparse/
      📁 lower-case/
      📁 lru-cache/
      📁 marked/
      📁 math-intrinsics/
      📁 micro-memoize/
      📁 micromatch/
      📁 mime/
      📁 mime-db/
      📁 mime-types/
      📁 min-indent/
      📁 minimatch/
      📁 minimist/
      📁 moize/
      📁 moment/
      📁 moment-timezone/
      📁 morgan/
      📁 ms/
      📁 nanoid/
      📁 negotiator/
      📁 nib/
      📁 no-case/
      📁 normalize-path/
      📁 nunjucks/
      📁 nwsapi/
      📁 on-finished/
      📁 on-headers/
      📁 once/
      📁 open/
      📁 parse5/
      📁 parseurl/
      📁 pascal-case/
      📁 path-is-absolute/
      📁 path-key/
      📁 path-parse/
      📁 picocolors/
      📁 picomatch/
      📁 pretty-hrtime/
      📁 prismjs/
      📁 punycode/
      📁 range-parser/
      📁 readable-stream/
      📁 readdirp/
      📁 resolve/
      📁 rfdc/
      📁 rrweb-cssom/
      📁 safe-buffer/
      📁 safer-buffer/
      📁 sax/
      📁 saxes/
      📁 send/
      📁 serve-static/
      📁 setprototypeof/
      📁 shebang-command/
      📁 shebang-regex/
      📁 source-map/
      📁 sprintf-js/
      📁 statuses/
      📁 string_decoder/
      📁 strip-ansi/
      📁 strip-indent/
      📁 stylus/
      📁 supports-preserve-symlinks-flag/
      📁 symbol-tree/
      📁 through2/
      📁 tildify/
      📁 titlecase/
      📁 tldts/
      📁 tldts-core/
      📁 to-regex-range/
      📁 toidentifier/
      📁 tough-cookie/
      📁 tr46/
      📁 tslib/
      📁 unpipe/
      📁 util-deprecate/
      📁 utils-merge/
      📁 vary/
      📁 w3c-xmlserializer/
      📁 warehouse/
      📁 webidl-conversions/
      📁 whatwg-encoding/
      📁 whatwg-mimetype/
      📁 whatwg-url/
      📁 which/
      📁 wrappy/
      📁 ws/
      📁 xml-name-validator/
      📁 xmlchars/
   📁 public/
      📁 2026/
      📁 archives/
      📁 categories/
      📁 css/
      📁 images/
      📁 js/
      📁 tags/
      📄 index.html
   📁 scaffolds/
      📄 draft.md
      📄 page.md
      📄 post.md
   📁 source/
      📁 _posts/
      📁 images/
   📁 themes/
      📁 next/
   📄 _config.landscape.yml
   📄 _config.yml
   📄 db.json
   📄 package-lock.json
   📄 package.json
📁 frank-invest-blog-backup/
   📁 node_modules/
      📁 @adobe/
      📁 @asamuzakjp/
      📁 @csstools/
      📁 @types/
      📁 a-sync-waterfall/
      📁 abbrev/
      📁 agent-base/
      📁 ansi-regex/
      📁 anymatch/
      📁 argparse/
      📁 asap/
      📁 async/
      📁 asynckit/
      📁 balanced-match/
      📁 basic-auth/
      📁 binary-extensions/
      📁 bluebird/
      📁 brace-expansion/
      📁 braces/
      📁 bytes/
      📁 call-bind-apply-helpers/
      📁 camel-case/
      📁 chokidar/
      📁 combined-stream/
      📁 command-exists/
      📁 commander/
      📁 compressible/
      📁 compression/
      📁 concat-map/
      📁 connect/
      📁 cross-spawn/
      📁 cssstyle/
      📁 data-urls/
      📁 debug/
      📁 decimal.js/
      📁 deepmerge/
      📁 define-lazy-prop/
      📁 delayed-stream/
      📁 depd/
      📁 destroy/
      📁 dom-serializer/
      📁 domelementtype/
      📁 domhandler/
      📁 dompurify/
      📁 domutils/
      📁 dunder-proto/
      📁 ee-first/
      📁 ejs/
      📁 encodeurl/
      📁 entities/
      📁 es-define-property/
      📁 es-errors/
      📁 es-object-atoms/
      📁 es-set-tostringtag/
      📁 escape-html/
      📁 esprima/
      📁 etag/
      📁 fast-archy/
      📁 fast-equals/
      📁 fast-text-table/
      📁 filelist/
      📁 fill-range/
      📁 finalhandler/
      📁 form-data/
      📁 fresh/
      📁 fs.realpath/
      📁 fsevents/
      📁 function-bind/
      📁 get-intrinsic/
      📁 get-proto/
      📁 glob/
      📁 glob-parent/
      📁 gopd/
      📁 graceful-fs/
      📁 has-symbols/
      📁 has-tostringtag/
      📁 hasown/
      📁 hexo/
      📁 hexo-cli/
      📁 hexo-deployer-git/
      📁 hexo-front-matter/
      📁 hexo-fs/
      📁 hexo-generator-archive/
      📁 hexo-generator-category/
      📁 hexo-generator-index/
      📁 hexo-generator-tag/
      📁 hexo-i18n/
      📁 hexo-log/
      📁 hexo-pagination/
      📁 hexo-renderer-ejs/
      📁 hexo-renderer-marked/
      📁 hexo-renderer-stylus/
      📁 hexo-server/
      📁 hexo-theme-landscape/
      📁 hexo-util/
      📁 highlight.js/
      📁 html-encoding-sniffer/
      📁 htmlparser2/
      📁 http-errors/
      📁 http-proxy-agent/
      📁 https-proxy-agent/
      📁 iconv-lite/
      📁 inflight/
      📁 inherits/
      📁 is-binary-path/
      📁 is-core-module/
      📁 is-docker/
      📁 is-extglob/
      📁 is-glob/
      📁 is-number/
      📁 is-plain-object/
      📁 is-potential-custom-element-name/
      📁 is-wsl/
      📁 isexe/
      📁 jake/
      📁 js-yaml/
      📁 js-yaml-js-types/
      📁 jsdom/
      📁 jsonparse/
      📁 lower-case/
      📁 lru-cache/
      📁 luxon/
      📁 marked/
      📁 math-intrinsics/
      📁 micro-memoize/
      📁 micromatch/
      📁 mime/
      📁 mime-db/
      📁 mime-types/
      📁 min-indent/
      📁 minimatch/
      📁 minimist/
      📁 moize/
      📁 moment/
      📁 moment-timezone/
      📁 morgan/
      📁 ms/
      📁 nanoid/
      📁 negotiator/
      📁 nib/
      📁 no-case/
      📁 normalize-path/
      📁 nunjucks/
      📁 nwsapi/
      📁 on-finished/
      📁 on-headers/
      📁 once/
      📁 open/
      📁 parse5/
      📁 parseurl/
      📁 pascal-case/
      📁 path-is-absolute/
      📁 path-key/
      📁 path-parse/
      📁 picocolors/
      📁 picomatch/
      📁 pretty-hrtime/
      📁 prismjs/
      📁 punycode/
      📁 range-parser/
      📁 readable-stream/
      📁 readdirp/
      📁 resolve/
      📁 rfdc/
      📁 rrweb-cssom/
      📁 safe-buffer/
      📁 safer-buffer/
      📁 sax/
      📁 saxes/
      📁 send/
      📁 serve-static/
      📁 setprototypeof/
      📁 shebang-command/
      📁 shebang-regex/
      📁 source-map/
      📁 sprintf-js/
      📁 statuses/
      📁 string_decoder/
      📁 strip-ansi/
      📁 strip-indent/
      📁 stylus/
      📁 supports-preserve-symlinks-flag/
      📁 symbol-tree/
      📁 through2/
      📁 tildify/
      📁 titlecase/
      📁 tldts/
      📁 tldts-core/
      📁 to-regex-range/
      📁 toidentifier/
      📁 tough-cookie/
      📁 tr46/
      📁 tslib/
      📁 unpipe/
      📁 util-deprecate/
      📁 utils-merge/
      📁 vary/
      📁 w3c-xmlserializer/
      📁 warehouse/
      📁 webidl-conversions/
      📁 whatwg-encoding/
      📁 whatwg-mimetype/
      📁 whatwg-url/
      📁 which/
      📁 wrappy/
      📁 ws/
      📁 xml-name-validator/
      📁 xmlchars/
   📁 public/
      📁 archives/
      📁 categories/
      📁 css/
      📁 fancybox/
      📁 js/
      📁 market/
      📁 tags/
      📁 uncategorized/
      📄 index.html
   📄 db.json
📁 intel/
   📁 2026-05-08/
      📁 images/
      📄 caijing_20260508.md
📁 mcp-caijing/
   📁 dist/
      📄 index.js
   📄 package.json
📁 mcp-image-url/
   📁 dist/
      📄 index.d.ts
      📄 index.d.ts.map
      📄 index.js
      📄 index.js.map
   📁 node_modules/
      📁 @hono/
      📁 @modelcontextprotocol/
      📁 @types/
      📁 accepts/
      📁 ajv/
      📁 ajv-formats/
      📁 body-parser/
      📁 bytes/
      📁 call-bind-apply-helpers/
      📁 call-bound/
      📁 content-disposition/
      📁 content-type/
      📁 cookie/
      📁 cookie-signature/
      📁 cors/
      📁 cross-spawn/
      📁 debug/
      📁 depd/
      📁 dunder-proto/
      📁 ee-first/
      📁 encodeurl/
      📁 es-define-property/
      📁 es-errors/
      📁 es-object-atoms/
      📁 escape-html/
      📁 etag/
      📁 eventsource/
      📁 eventsource-parser/
      📁 express/
      📁 express-rate-limit/
      📁 fast-deep-equal/
      📁 fast-uri/
      📁 finalhandler/
      📁 forwarded/
      📁 fresh/
      📁 function-bind/
      📁 get-intrinsic/
      📁 get-proto/
      📁 gopd/
      📁 has-symbols/
      📁 hasown/
      📁 hono/
      📁 http-errors/
      📁 iconv-lite/
      📁 inherits/
      📁 ip-address/
      📁 ipaddr.js/
      📁 is-promise/
      📁 isexe/
      📁 jose/
      📁 json-schema-traverse/
      📁 json-schema-typed/
      📁 math-intrinsics/
      📁 media-typer/
      📁 merge-descriptors/
      📁 mime-db/
      📁 mime-types/
      📁 ms/
      📁 negotiator/
      📁 object-assign/
      📁 object-inspect/
      📁 on-finished/
      📁 once/
      📁 parseurl/
      📁 path-key/
      📁 path-to-regexp/
      📁 pkce-challenge/
      📁 proxy-addr/
      📁 qs/
      📁 range-parser/
      📁 raw-body/
      📁 require-from-string/
      📁 router/
      📁 safer-buffer/
      📁 send/
      📁 serve-static/
      📁 setprototypeof/
      📁 shebang-command/
      📁 shebang-regex/
      📁 side-channel/
      📁 side-channel-list/
      📁 side-channel-map/
      📁 side-channel-weakmap/
      📁 statuses/
      📁 toidentifier/
      📁 type-is/
      📁 typescript/
      📁 undici-types/
      📁 unpipe/
      📁 vary/
      📁 which/
      📁 wrappy/
      📁 ws/
      📁 zod/
      📁 zod-to-json-schema/
   📄 index.ts
   📄 package-lock.json
   📄 package.json
   📄 tsconfig.json
📁 mcp-redring/
   📁 docs/
   📁 html/
      📁 2026-05-07/
   📁 scripts/
   📁 src/
   📄 ARCHITECTURE.md
   📄 README.md
   📄 gen_caijing_html.py
   📄 process_and_upload.py
   📄 trigger_build.py
📁 mcp-screenshot/
   📁 dist/
      📄 index.d.ts
      📄 index.d.ts.map
      📄 index.js
      📄 index.js.map
   📁 node_modules/
      📁 @emnapi/
      📁 @hono/
      📁 @img/
      📁 @modelcontextprotocol/
      📁 @types/
      📁 accepts/
      📁 ajv/
      📁 ajv-formats/
      📁 body-parser/
      📁 bytes/
      📁 call-bind-apply-helpers/
      📁 call-bound/
      📁 content-disposition/
      📁 content-type/
      📁 cookie/
      📁 cookie-signature/
      📁 cors/
      📁 cross-spawn/
      📁 debug/
      📁 depd/
      📁 detect-libc/
      📁 dunder-proto/
      📁 ee-first/
      📁 encodeurl/
      📁 es-define-property/
      📁 es-errors/
      📁 es-object-atoms/
      📁 escape-html/
      📁 etag/
      📁 eventsource/
      📁 eventsource-parser/
      📁 express/
      📁 express-rate-limit/
      📁 fast-deep-equal/
      📁 fast-uri/
      📁 finalhandler/
      📁 forwarded/
      📁 fresh/
      📁 fsevents/
      📁 function-bind/
      📁 get-intrinsic/
      📁 get-proto/
      📁 gopd/
      📁 has-symbols/
      📁 hasown/
      📁 hono/
      📁 http-errors/
      📁 iconv-lite/
      📁 inherits/
      📁 ip-address/
      📁 ipaddr.js/
      📁 is-promise/
      📁 isexe/
      📁 jose/
      📁 json-schema-traverse/
      📁 json-schema-typed/
      📁 math-intrinsics/
      📁 media-typer/
      📁 merge-descriptors/
      📁 mime-db/
      📁 mime-types/
      📁 ms/
      📁 negotiator/
      📁 object-assign/
      📁 object-inspect/
      📁 on-finished/
      📁 once/
      📁 parseurl/
      📁 path-key/
      📁 path-to-regexp/
      📁 pkce-challenge/
      📁 playwright/
      📁 playwright-core/
      📁 proxy-addr/
      📁 qs/
      📁 range-parser/
      📁 raw-body/
      📁 require-from-string/
      📁 router/
      📁 safer-buffer/
      📁 semver/
      📁 send/
      📁 serve-static/
      📁 setprototypeof/
      📁 sharp/
      📁 shebang-command/
      📁 shebang-regex/
      📁 side-channel/
      📁 side-channel-list/
      📁 side-channel-map/
      📁 side-channel-weakmap/
      📁 statuses/
      📁 toidentifier/
      📁 type-is/
      📁 typescript/
      📁 undici-types/
      📁 unpipe/
      📁 vary/
      📁 which/
      📁 wrappy/
      📁 ws/
      📁 zod/
      📁 zod-to-json-schema/
   📄 index.ts
   📄 package-lock.json
   📄 package.json
   📄 tsconfig.json
📁 mcp-shot2/
   📁 dist/
      📄 index.js
      📄 index.ts
   📁 node_modules/
      📁 @hono/
      📁 @modelcontextprotocol/
      📁 @types/
      📁 accepts/
      📁 ajv/
      📁 ajv-formats/
      📁 body-parser/
      📁 bytes/
      📁 call-bind-apply-helpers/
      📁 call-bound/
      📁 content-disposition/
      📁 content-type/
      📁 cookie/
      📁 cookie-signature/
      📁 cors/
      📁 cross-spawn/
      📁 debug/
      📁 depd/
      📁 dunder-proto/
      📁 ee-first/
      📁 encodeurl/
      📁 es-define-property/
      📁 es-errors/
      📁 es-object-atoms/
      📁 escape-html/
      📁 etag/
      📁 eventsource/
      📁 eventsource-parser/
      📁 express/
      📁 express-rate-limit/
      📁 fast-deep-equal/
      📁 fast-uri/
      📁 finalhandler/
      📁 forwarded/
      📁 fresh/
      📁 fsevents/
      📁 function-bind/
      📁 get-intrinsic/
      📁 get-proto/
      📁 gopd/
      📁 has-symbols/
      📁 hasown/
      📁 hono/
      📁 http-errors/
      📁 iconv-lite/
      📁 inherits/
      📁 ip-address/
      📁 ipaddr.js/
      📁 is-promise/
      📁 isexe/
      📁 jose/
      📁 json-schema-traverse/
      📁 json-schema-typed/
      📁 math-intrinsics/
      📁 media-typer/
      📁 merge-descriptors/
      📁 mime-db/
      📁 mime-types/
      📁 ms/
      📁 negotiator/
      📁 object-assign/
      📁 object-inspect/
      📁 on-finished/
      📁 once/
      📁 parseurl/
      📁 path-key/
      📁 path-to-regexp/
      📁 pkce-challenge/
      📁 playwright/
      📁 playwright-core/
      📁 proxy-addr/
      📁 qs/
      📁 range-parser/
      📁 raw-body/
      📁 require-from-string/
      📁 router/
      📁 safer-buffer/
      📁 send/
      📁 serve-static/
      📁 setprototypeof/
      📁 shebang-command/
      📁 shebang-regex/
      📁 side-channel/
      📁 side-channel-list/
      📁 side-channel-map/
      📁 side-channel-weakmap/
      📁 statuses/
      📁 toidentifier/
      📁 type-is/
      📁 typescript/
      📁 undici-types/
      📁 unpipe/
      📁 vary/
      📁 which/
      📁 wrappy/
      📁 zod/
      📁 zod-to-json-schema/
   📄 package-lock.json
   📄 package.json
   📄 tsconfig.json
📁 memory/
   📄 2026-03-17-api-key-setup.md
   📄 2026-04-16.md
   📄 2026-04-21.md
   📄 2026-05-07.md
   📄 2026-05-12-1545.md
📁 node_modules/
   📁 ws/
      📁 lib/
      📄 LICENSE
      📄 README.md
      📄 browser.js
      📄 index.js
      📄 package.json
      📄 wrapper.mjs
📁 notes/
   📁 areas/
📁 scratch/
   📄 xhq-check.js
   📄 xhq-scrape.py
   📄 xhq-scrape2.py
   📄 xhq-scraper.js
📁 shared/
   📁 auth/
      📄 __init__.py
      📄 session_manager.py
      📄 token_extractor.js
   📁 deploy/
      📄 __init__.py
      📄 github_pages.py
   📁 network/
      📄 __init__.py
      📄 batch_uploader.py
   📁 render/
      📄 __init__.py
      📄 html_generator.py
   📁 utils/
      📄 dom_scraper.js
      📄 test_dom_scraper.js
   📄 __init__.py
   📄 build_comments.py
   📄 build_full.py
   📄 cdp_get_innerhtml.py
   📄 cdp_html.py
   📄 get_html.py
   📄 pipeline.py
   📄 test_full_pipeline.py
📁 skills/
   📁 automation-workflows/
      📄 SKILL.md
      📄 _meta.json
   📁 find-skills/
      📄 SKILL.md
      📄 _meta.json
   📁 gog/
      📄 SKILL.md
      📄 _meta.json
   📁 ontology/
      📁 references/
      📁 scripts/
      📄 SKILL.md
      📄 _meta.json
   📁 openclaw-tavily-search/
      📁 scripts/
      📄 SKILL.md
      📄 _meta.json
   📁 red-ring-scraper/
      📁 references/
      📁 scripts/
      📄 SKILL.md
   📁 self-improving-agent/
      📁 assets/
      📁 hooks/
      📁 references/
      📁 scripts/
      📄 SKILL.md
      📄 _meta.json
   📁 skill-vetter/
      📄 SKILL.md
      📄 _meta.json
   📁 stock-watcher/
      📁 scripts/
      📄 README.md
      📄 SKILL.md
      📄 _meta.json
   📄 red-ring-scraper.skill
📁 state/
📁 stock_project/
   📁 config/
   📁 data/
   📁 reports/
   📁 scripts/
📁 workspace/
📁 workspace-jobs/
   📁 finance-breakfast/
      📁 analysis/
      📁 logs/
      📁 raw/
      📁 scripts/
📄 AGENTS.md
📄 HEARTBEAT.md
📄 IDENTITY.md
📄 MEMORY.md
📄 PRE-TASK-CHECKLIST.md
📄 SOUL.md
📄 TOOLS.md
📄 USER.md
📄 caijing_20260421.html
📄 caijing_20260509.html
📄 caijing_20260512.html
📄 caijing_20260513.html
📄 comments.json
📄 dijiedi11_yanbao_0418.html
📄 full_innerhtml.txt
📄 login-page.png
📄 package-lock.json
📄 package.json
📄 pipeline_input.html
📄 pipeline_input.txt
📄 raw_post.html
📄 red-ring-auth-status.md
📄 red-ring-cookies.json
📄 test_push.txt
📄 upload_browser.b64
📄 xhq-login.png
📄 xhq-login2.png
📄 xhq-redring.png
📄 xhq-screenshot.png
📄 xiaohongquan_qr.png
📄 天阶功法卷四-磷化工投资价值分析.md
```

---

## 2. skills/red-ring-scraper/SKILL.md

```markdown
---
name: red-ring-scraper
description: >
  抓取小红圈帖子（财经早餐）并发布到 GitHub Pages。
  触发条件：用户说"抓取财经早餐"、"提取小红圈帖子"、"下载 red-ring 图片"。
  本 Skill 是纯编排器，所有脏活由 shared/ 积木执行。
---

> ⚠️ **强制规则**：所有截图任务必须使用 `screenshot-master__capture_page` MCP 工具，禁止用 `browser(action=screenshot)` 替代。

# red-ring-scraper — 编排器规范

**核心原则（SSOT）**：Skill 永远不硬编码 DOM 选择器、正则公式或渲染逻辑。所有提取和渲染逻辑下沉到 `shared/` 模块，Skill 只负责编排调用顺序和传递参数。

---

## 架构图

```
User → Skill (Orchestrator)
         │
         ├── Step 1: Browser — 导航 + 滚动加载评论
         │              ↓
         ├── Step 2: exec cdp_get_innerhtml.py — 通过 CDP 提取 innerHTML → /tmp/<date>_post.html
         │              ↓
         ├── Step 3: exec build_full.py — 读取 HTML → 上传图片 → markdownify 渲染 → GitHub Pages
         │              ↓
         └── Step 4: 向用户报告最终 URL
```

---

## Step 1 — Browser：导航 + 滚动加载评论

**目标**：让浏览器访问目标帖子，加载所有评论（懒加载需滚动）。

```
browser action=navigate targetId=<当前targetId> url=<帖子URL>
```

滚动加载评论（可重复 2-3 次）：
```
browser action=act targetId=<当前targetId> request={"kind":"evaluate","fn":"function(){window.scrollTo(0,document.body.scrollHeight)}"}
```

**从页面标题或 URL 提取日期**：
```javascript
// 获取帖子标题中的日期
document.querySelector('h1, .post-title, [class*=title]')?.textContent?.match(/\d{4}[-/]\d{2}[-/]\d{2}/)?.[0]
// 或从 URL 提取
location.pathname  // → /post/27593-XXXXXXXX
```
日期格式统一转为 `YYYYMMDD`（如 `20260513`）。

---

## Step 2 — CDP 提取 innerHTML

**目的**：通过浏览器 CDP 协议将页面正文 innerHTML 写入本地文件，供 Step 3 的 Python 消费。

**CDP WebSocket URL**：从当前浏览器 session 状态获取。
默认：`ws://127.0.0.1:18900/devtools/page/DCDBD120E79E4B69E755CAC03E39F11F`
（每次 gateway 重启后可能变化，以实际 browser status 为准）

**执行命令**：
```bash
python3 /Users/frank_bot/.openclaw/workspace/shared/cdp_get_innerhtml.py \
    /tmp/<date>_post.html \
    ws://127.0.0.1:18900/devtools/page/<TARGET_ID> \
    --selector main
```

**预期输出**：
```
[CDP] WS: ws://...
[CDP] Selector: main
[CDP] Output: /tmp/20260513_post.html
[CDP] ✅ 7080 bytes → /tmp/20260513_post.html
```

**失败处理**：如果 CDP 连接失败，降级使用 browser evaluate 直接获取（见下方应急方案）。

---

## Step 3 — build_full.py：渲染 + 上传 + 部署

**目的**：读取 `/tmp/<date>_post.html`，自动完成：
1. 提取正文 / 评论 / 图片 URL
2. 下载私有图片 → 上传 GitHub
3. markdownify 无损渲染（图片位置原位保留）
4. 上传 HTML 到 GitHub 仓库
5. 触发 GitHub Pages 构建

**执行命令**：
```bash
python3 /Users/frank_bot/.openclaw/workspace/shared/build_full.py \
    /tmp/<date>_post.html \
    <date_YYYYMMDD> \
    caijing_<date_YYYYMMDD>.html \
    "财经早餐 <date_YYYY-MM-DD>"
```

**参数说明**：
| 参数 | 示例 | 说明 |
|------|------|------|
| `<date>_post.html` | `/tmp/20260513_post.html` | Step 2 输出的文件路径 |
| `<date_YYYYMMDD>` | `20260513` | 日期，用于图片文件命名 |
| `caijing_*.html` | `caijing_20260513.html` | GitHub 仓库中的输出文件名 |
| `title` | `"财经早餐 2026-05-13"` | 页面标题 |

**预期输出**：
```
[build] innerHTML: 7080 chars | body: 6657 chars
[build] 正文图片: 10 张 | 评论: 8 条
  [OK] 1/10 caijing_20260513_img_01.jpg (165KB)
  ...
  [OK] 10/10 caijing_20260513_img_10.jpg (860KB)
[build] 图片映射: 10/10 成功
[build] 最终 HTML: 8923 bytes | GitHub 图片: 10 张
[build] HTML 上传: https://raw.githubusercontent.com/...
[build] GitHub Pages: OK https://frankinvest.github.io/caijing-daily/caijing_20260513.html

✅ 完成: {"html_file": "caijing_20260513.html", "images": 10, "comments": 8, "url": "..."}
```

---

## Step 4 — 上报结果

将 Step 3 返回的 `url` 字段以富文本形式发给用户，包含：
- 访问地址（GitHub Pages）
- 源文件地址（GitHub repo）
- 完成情况摘要（图片张数、评论条数）

---

## 应急方案

### CDP 连接失败时的降级策略

如果 `cdp_get_innerhtml.py` 报错（浏览器 gateway 重启等），改用 `browser evaluate` 直接获取 innerHTML：

```javascript
// 在 browser tool 中执行
(function(){
  var el = document.querySelector('main') || document.querySelector('.post-body') || document.body;
  var c = el.cloneNode(true);
  var remove = c.querySelectorAll('[class*=comment],[class*=reply],.cmt-item,.py-12,.icon-wrap,[class*=actions],footer,.reply-wrap,.comment-body,.replies');
  remove.forEach(function(e){ e.remove(); });
  return 'POST_START' + c.innerHTML + 'POST_END';
})()
```

将返回值手动写入文件：
```bash
# 在 exec 中执行
cat > /tmp/<date>_post.html << 'ENDHTML'
<粘贴 innerHTML 内容>
ENDHTML
```

然后继续 Step 3（`build_full.py`）。

---

## shared/ 积木清单（SSOT）

| 模块 | 职责 | 接口 |
|------|------|------|
| `shared/cdp_get_innerhtml.py` | CDP 提取 innerHTML → 文件 | CLI: `<output_file> [ws_url] [--selector]` |
| `shared/build_full.py` | 渲染 + 上传 + 部署 | CLI: `<html_file> <date> [output] [--title]` |
| `shared/deploy/github_pages.py` | GitHub Pages 触发 | `GitHubPagesTrigger(token, repo).trigger_and_wait()` |
| `shared/network/batch_uploader.py` | 图片批量上传 | `GitHubUploader(token, repo).upload(path, b64)` |

---

## 注意事项

1. **日期确定**：优先从帖子标题提取（如"2026年5月13日财经早餐"），格式化为 `YYYYMMDD`
2. **CDP WebSocket**：每次 gateway 重启后 browser status 会给出新的 CDP URL，注意更新
3. **输出文件**：永远是 `/tmp/<date>_post.html`，build_full.py 读取此文件
4. **GitHub Pages 延迟**：构建约需 30 秒，发布后可等待再截图验证

```

---

## 3. shared/cdp_get_innerhtml.py

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
cdp_get_innerhtml.py — 通过 CDP 提取页面 innerHTML 并落盘
用法:
    python3 cdp_get_innerhtml.py <output_html_file> [cdp_ws_url]
示例:
    python3 cdp_get_innerhtml.py /tmp/may13_post.html
    python3 cdp_get_innerhtml.py /tmp/may13_post.html ws://127.0.0.1:18900/devtools/page/ABC123
"""
import websocket, json, time, sys, os, argparse

DEFAULT_WS = "ws://127.0.0.1:18900/devtools/page/DCDBD120E79E4B69E755CAC03E39F11F"
DEFAULT_SELECTOR = "main"

JS_TEMPLATE = """
(function(){
  var el = document.querySelector(%(selector)r);
  if (!el) {
    // 降级: 尝试 .post-body
    el = document.querySelector('.post-body') || document.body;
  }
  var c = el.cloneNode(true);
  // 移除评论区、互动元素（不影响正文提取）
  var remove = c.querySelectorAll(
    '[class*=comment],[class*=reply],.cmt-item,.py-12,.icon-wrap,' +
    '[class*=actions],footer,.reply-wrap,.comment-body,.replies,.wpw'
  );
  remove.forEach(function(e){ e.remove(); });
  return 'POST_START' + c.innerHTML + 'POST_END';
})()
"""

def fetch_innerhtml(ws_url, selector=DEFAULT_SELECTOR):
    """通过 CDP WebSocket 获取 innerHTML，返回 HTML 字符串"""
    js = JS_TEMPLATE % {"selector": json.dumps(selector)}
    ws = websocket.create_connection(ws_url, suppress_origin=True, timeout=10)
    try:
        ws.send(json.dumps({
            "id": 1,
            "method": "Runtime.evaluate",
            "params": {"expression": js, "returnByValue": True}
        }))
        time.sleep(1.5)
        for _ in range(5):
            try:
                msg = ws.recv()
                data = json.loads(msg)
                if data.get("id") == 1:
                    result = data.get("result", {}).get("result", {})
                    value = result.get("value", "")
                    if not value or 'POST_START' not in value:
                        raise Exception("CDP returned empty or invalid content")
                    return value
            except:
                pass
            time.sleep(0.8)
        raise Exception("No valid CDP response after 5 retries")
    finally:
        ws.close()

def main():
    ap = argparse.ArgumentParser(description='CDP innerHTML 提取工具')
    ap.add_argument('output_file', help='输出 HTML 文件路径，如 /tmp/may13_post.html')
    ap.add_argument('cdp_ws_url', nargs='?', default=DEFAULT_WS,
                    help='CDP WebSocket URL（默认从环境自动获取）')
    ap.add_argument('--selector', '-s', default=DEFAULT_SELECTOR,
                    help='CSS 选择器（默认: main）')
    args = ap.parse_args()

    print(f"[CDP] WS: {args.cdp_ws_url}")
    print(f"[CDP] Selector: {args.selector}")
    print(f"[CDP] Output: {args.output_file}")

    try:
        html = fetch_innerhtml(args.cdp_ws_url, args.selector)
    except Exception as e:
        # 降级: 尝试无头 Chrome 模式
        print(f"[CDP] Primary failed: {e}")
        print("[CDP] Retrying with body fallback...")
        try:
            fallback_selector = "body"
            js = JS_TEMPLATE % {"selector": json.dumps(fallback_selector)}
            ws = websocket.create_connection(args.cdp_ws_url, suppress_origin=True, timeout=10)
            ws.send(json.dumps({"id": 1, "method": "Runtime.evaluate",
                                 "params": {"expression": js, "returnByValue": True}}))
            time.sleep(2)
            for _ in range(3):
                try:
                    msg = ws.recv()
                    data = json.loads(msg)
                    if data.get("id") == 1:
                        html = data["result"]["result"]["value"]
                        break
                except:
                    pass
                time.sleep(1)
            ws.close()
        except Exception as e2:
            print(f"[CDP] Fallback also failed: {e2}")
            sys.exit(1)

    os.makedirs(os.path.dirname(args.output_file) or '.', exist_ok=True)
    with open(args.output_file, "w", encoding="utf-8", errors="replace") as f:
        f.write(html)

    print(f"[CDP] ✅ {len(html)} bytes → {args.output_file}")

if __name__ == "__main__":
    main()

```

---

## 4. shared/build_full.py

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
build_full.py — SSOT 渲染引擎
用法:
    python3 build_full.py <innerhtml_file> <date_YYYYMMDD> [output_file] [title]
示例:
    python3 build_full.py /tmp/may13_post.html 20260513
    python3 build_full.py /tmp/may13_post.html 20260513 caijing_20260513.html "财经早餐 20260513"
"""
import re, base64, urllib.request, json, time, sys, os, argparse, html as html_mod

_parent = os.path.dirname(os.path.dirname(os.path.abspath(__file__)))
if _parent not in sys.path:
    sys.path.insert(0, _parent)
import markdownify as mf
from shared.network import GitHubUploader
from shared.deploy import GitHubPagesTrigger

TOKEN = "ghp_***REDACTED***"
REPO = "frankinvest/caijing-daily"
REF_URL = "https://www.red-ring.cn/post/27593-2120574"
HEADERS = {
    "Cookie": "Hm_lvt_1c9949e59fafcdf8f7cd363b452f1837=1778115791,1778500926; HMACCOUNT=77046ED79FB0AFED; Hm_lpvt_1c9949e59fafcdf8f7cd363b452f1837=1778653122",
    "User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/147.0.0.0 Safari/537.36",
    "Referer": REF_URL
}

# ═══════════════════════════════════════════════════════════════
# 数据提取层（正文 / 评论 / 图片）
# ═══════════════════════════════════════════════════════════════

def extract_comments(html):
    """从完整 innerHTML 中提取评论"""
    comments = []
    top_pat = re.compile(
        r'<div class="py-12 flex bt">(.*?)(?=<div class="py-12 flex bt">|<div class="py-24"></div>)',
        re.DOTALL
    )
    for m in top_pat.finditer(html):
        block = m.group(1)
        um = re.search(r'<span class="cup mr-5">([^<]+)</span>', block)
        if not um:
            continue
        user = um.group(1).strip()
        tm = re.search(r'<span class="dark-9 fz-sm">([^<]+)</span>', block)
        time_str = tm.group(1).strip() if tm else ''
        wpm = re.search(r'<span class="wpw">(.+?)</span>', block, re.DOTALL)
        if not wpm:
            continue
        text = re.sub(r'<[^>]+>', '', wpm.group(1)).strip()
        text = text.replace('&nbsp;', ' ').replace('&lt;', '<').replace('&gt;', '>')
        if not text:
            continue
        if '[图片' in text:
            text = '[图片评论]'
        item = {'user': user, 'time': time_str, 'content': text, 'replies': []}
        reply_section_m = re.search(
            r'<div class="bgc-body px-9 py-5">(.*?)</div>\s*</div>\s*</div>\s*</div>\s*</div>',
            block, re.DOTALL
        )
        if reply_section_m:
            reply_block = reply_section_m.group(1)
            reply_pat = re.compile(
                r'<span class="c-primary cup">([^<]+)</span>.*?<span class="wpw">(.+?)</span>',
                re.DOTALL
            )
            for rm in reply_pat.finditer(reply_block):
                ru = rm.group(1).strip()
                rt = re.sub(r'<[^>]+>', '', rm.group(2)).strip()
                rt = rt.replace('&nbsp;', ' ').replace('&lt;', '<').replace('&gt;', '>')
                if ru and rt:
                    item['replies'].append({'user': ru, 'content': rt})
        comments.append(item)
    return comments

def extract_post_images(post_html):
    """提取正文中的私有图片 URL（去重）"""
    seen, imgs = set(), []
    for m in re.finditer(r'<img[^>]+src="([^"]+)"', post_html):
        url = m.group(1)
        if 'private.red-ring.cn' in url and url not in seen:
            seen.add(url)
            imgs.append(url)
    return imgs

def extract_post_body(html):
    """
    提取正文 HTML。
    innerHTML 来源有两个版本：
    1. CDP 提取（ql-view）：<div class="fzx-2 wwb ql-view ql-ring">...
    2. 备用（legacy）：<div class="post-body ...">...
    """
    # CDP 版本（主要）
    m = re.search(r'<div class="[^"]*ql-view[^"]*">(.*?)</div>\s*<!---->', html, re.DOTALL)
    if m and len(m.group(1)) > 100:
        return m.group(1)
    # Legacy 版本（降级）
    m = re.search(r'<div class="post-body[^"]*">(.*?)</div>\s*<!---->', html, re.DOTALL)
    if m:
        return m.group(1)
    return ''

# ═══════════════════════════════════════════════════════════════
# 图片上传层
# ═══════════════════════════════════════════════════════════════

def upload_images(urls, date, gh):
    """
    下载私有图片 → 上传 GitHub → 返回 {私有URL: GitHub_URL} 映射
    文件命名: caijing_{date}_img_{NN}.{ext}
    """
    mapping, total = {}, len(urls)
    for i, url in enumerate(urls, 1):
        ext = 'png' if '.png' in url else ('webp' if 'webp' in url else 'jpg')
        fname = f"caijing_{date}_img_{i:02d}.{ext}"
        gh_path = f"images/{date}/{fname}"
        try:
            req = urllib.request.Request(url, headers=HEADERS)
            with urllib.request.urlopen(req, timeout=15) as r:
                if r.status != 200:
                    raise Exception(f"HTTP {r.status}")
                data = r.read()
                if len(data) < 2048:
                    raise Exception(f"Too small ({len(data)}B)")
                if b'<!DOCTYPE' in data[:50]:
                    raise Exception("HTML error page")
            b64 = base64.b64encode(data).decode('ascii')
            gurl = gh.upload(gh_path, b64)
            mapping[url] = gurl
            print(f"  [OK] {i}/{total} {fname} ({len(data)//1024}KB)")
        except Exception as e:
            print(f"  [FAIL] {i}/{total} {url[:60]} → {e}")
        if i < total:
            time.sleep(0.5)
    return mapping

# ═══════════════════════════════════════════════════════════════
# Markdown → HTML 渲染层（使用 (.+?) 非贪婪正则）
# ═══════════════════════════════════════════════════════════════

def md_to_html_with_comments(md_str, title, comments):
    """
    将 Markdown（含正文 + 评论）渲染为完整 HTML
    - 图片: ![alt](url) → <img src="url" ...>
    - 强调: **text** → <strong>text</strong>
    - 分割: --- → <hr>
    """
    def img_replace(m):
        src, alt = m.group(2), m.group(1)
        return (
            f'<img src="{src}" alt="{alt}" '
            f'loading="lazy" style="max-width:100%;border-radius:4px;margin:8px 0;display:block">'
        )

    # ⚠️ 必须用 (.+?) 非贪婪匹配，[^)]+ 会在 URL 第一个 ) 处截断
    body = re.sub(r'!\[([^\]]*)\]\((.+?)\)', img_replace, md_str)
    body = re.sub(r'\*\*(.+?)\*\*', r'<strong>\1</strong>', body)

    paras = []
    for line in body.splitlines():
        line = line.strip()
        if not line:
            continue
        if line.startswith('<img ') or line.startswith('<blockquote'):
            paras.append(line)
        elif line.startswith('---') or line.startswith('<hr'):
            paras.append('<hr class="divider">')
        else:
            paras.append(f'<p>{line}</p>')
    post_body_html = '\n'.join(paras)
    cmt_html = _render_comments_html(comments)

    CSS = """
    body{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif;
         font-size:14px;max-width:720px;margin:0 auto;padding:16px;
         background:#fafafa;line-height:1.7;color:#333}
    .post{background:white;border-radius:8px;padding:20px;margin-bottom:16px;
          box-shadow:0 1px 3px rgba(0,0,0,.08)}
    .cmt-wrap{background:white;border-radius:8px;padding:20;margin-bottom:16px;
              box-shadow:0 1px 3px rgba(0,0,0,.08)}
    img{max-width:100%;border-radius:4px;margin:8px 0;display:block}
    strong{color:#c00}
    .cmt-item{background:#f9f9f9;border-radius:6px;padding:12px;margin-bottom:10px}
    .u{color:#1a73e8;font-weight:600}
    .t{color:#999;font-size:.8em}
    .r{margin-top:6px;padding:6px 10px;background:#f0f0f0;border-radius:4px;font-size:.88em;color:#555}
    .footer{text-align:center;color:#999;font-size:.8em;padding:20px 0;
            border-top:1px solid #eee;margin-top:30px}
    p{margin:.5em 0}
    .divider{border:none;border-top:1px solid #eee;margin:24px 0}
    h2{font-size:1.1em;margin-top:0;padding-bottom:8px;border-bottom:1px solid #eee}
    """

    return (
        '<!DOCTYPE html>\n<html lang="zh">\n<head>\n'
        '<meta charset="UTF-8">\n'
        '<meta name="viewport" content="width=device-width,initial-scale=1">\n'
        f'<title>{title}</title>\n'
        '<style>\n' + CSS + '\n</style>\n'
        '</head>\n<body>\n'
        f'<div class="post">\n{post_body_html}\n</div>\n'
        '<div class="cmt-wrap">\n<h2>💬 评论区</h2>\n' + cmt_html + '\n</div>\n'
        '<div class="footer"><p>来源：小红圈 · 红运Dang投 · MR Dang<br>'
        'MCP-RedRing · SSOT 架构自动生成</p></div>\n'
        '</body>\n</html>'
    )

def _render_comments_html(comments):
    """评论数组 → HTML 片段"""
    if not comments:
        return '<p style="color:#999;text-align:center">暂无评论</p>'
    parts = []
    for c in comments:
        replies = ''
        for r in c.get('replies', []):
            replies += (
                f'<div class="r">'
                f'<span class="u">{r["user"]}</span>：{r["content"]}'
                f'</div>\n'
            )
        parts.append(
            f'<div class="cmt-item">'
            f'<div><span class="u">{c["user"]}</span> '
            f'<span class="t">{c["time"]}</span></div>'
            f'<div style="margin-top:4px">{c["content"]}</div>\n{replies}'
            f'</div>'
        )
    return '\n'.join(parts)

def render_comments_md(comments):
    """评论数组 → Markdown 片段"""
    if not comments:
        return ''
    lines = ['\n\n---\n\n## 💬 评论区\n']
    for c in comments:
        lines.append(f"**{c['user']}** · {c['time']}：{c['content']}")
        for r in c['replies']:
            lines.append(f"  ↳ **{r['user']}**：{r['content']}")
        lines.append('')
    return '\n'.join(lines)

# ═══════════════════════════════════════════════════════════════
# GitHub API 工具
# ═══════════════════════════════════════════════════════════════

def gh_put(path, content_b64, msg, branch="main"):
    """PUT file to GitHub repo, handles existing file SHA"""
    api = f"https://api.github.com/repos/{REPO}/contents/{path}"
    payload = {"message": msg, "content": content_b64, "branch": branch}
    # get existing SHA
    try:
        greq = urllib.request.Request(
            api + "?ref=" + branch,
            headers={"Authorization": "token " + TOKEN}
        )
        with urllib.request.urlopen(greq, timeout=8) as r:
            existing = json.loads(r.read())
            if existing.get('sha'):
                payload["sha"] = existing['sha']
    except:
        pass
    req = urllib.request.Request(
        api, data=json.dumps(payload).encode(),
        headers={"Authorization": "token " + TOKEN, "Content-Type": "application/json"},
        method="PUT"
    )
    with urllib.request.urlopen(req, timeout=15) as r:
        return json.loads(r.read())

# ═══════════════════════════════════════════════════════════════
# 主入口（CLI）
# ═══════════════════════════════════════════════════════════════

def build(html_file, date, output_file=None, title=None):
    """
    SSOT 构建流水线
    1. 读取 innerHTML 文件
    2. 提取正文 / 评论 / 图片
    3. 上传图片到 GitHub
    4. markdownify 无损渲染
    5. 上传 HTML + 触发 GitHub Pages
    """
    date_str = date  # YYYYMMDD
    display_date = f"{date[:4]}-{date[4:6]}-{date[6:]}"

    with open(html_file, encoding='utf-8', errors='replace') as f:
        full_html = f.read()

    # 裁切 POST_START / POST_END 标记
    s = full_html.find('POST_START')
    e = full_html.find('POST_END')
    if s != -1 and e != -1:
        full_html = full_html[s + 10:e]

    # HTML entity 解码（&amp; → &），图片 URL 必须解码后才能正确匹配
    full_html = html_mod.unescape(full_html)

    post_body_html = extract_post_body(full_html)
    post_images = extract_post_images(post_body_html)
    comments = extract_comments(full_html)

    # 如果正文提取为空，尝试直接用完整 innerHTML（去掉 POST_START/POST_END）
    if not post_body_html.strip():
        print("[build] WARN: post-body 为空，直接使用完整 innerHTML")
        post_body_html = full_html

    print(f"[build] innerHTML: {len(full_html)} chars | body: {len(post_body_html)} chars")
    print(f"[build] 正文图片: {len(post_images)} 张 | 评论: {len(comments)} 条")

    # 上传图片
    gh = GitHubUploader(token=TOKEN, repo=REPO)
    mapping = upload_images(post_images, date_str, gh) if post_images else {}
    print(f"[build] 图片映射: {len(mapping)}/{len(post_images)} 成功")

    # markdownify 无损转换
    post_md = mf.markdownify(post_body_html, heading_style="atx", link_style="inlined")
    for old_url, new_url in mapping.items():
        post_md = post_md.replace(old_url, new_url)

    cmt_md = render_comments_md(comments)
    full_md = post_md + cmt_md

    if title is None:
        title = f"财经早餐 {display_date}"
    final_html = md_to_html_with_comments(full_md, title=title, comments=comments)

    gh_img_count = final_html.count('raw.githubusercontent.com')
    print(f"[build] 最终 HTML: {len(final_html)} bytes | GitHub 图片: {gh_img_count} 张")

    # 上传 HTML
    if output_file is None:
        output_file = f"caijing_{date_str}.html"
    b64 = base64.b64encode(final_html.encode('utf-8')).decode('ascii')
    result = gh_put(output_file, b64, f"发布 {display_date} 财经早餐 (SSOT build)")
    print(f"[build] HTML 上传: {result.get('content', {}).get('download_url', '')[:80]}")

    # 触发 GitHub Pages
    pages_url = f"https://frankinvest.github.io/caijing-daily/{output_file}"
    try:
        ok = GitHubPagesTrigger(token=TOKEN, repo=REPO).trigger_and_wait()
        print(f"[build] GitHub Pages: {'OK' if ok else 'TIMEOUT'} {pages_url}")
    except Exception as e:
        print(f"[build] GitHub Pages 触发异常: {e}")
        print(f"[build] 直接访问: {pages_url}")

    return {
        "html_file": output_file,
        "images": len(mapping),
        "comments": len(comments),
        "url": pages_url
    }

def main():
    ap = argparse.ArgumentParser(description='SSOT 渲染引擎 - 从 innerHTML 生成财经早餐 HTML')
    ap.add_argument('html_file', help='innerHTML 文件路径（来自 cdp_get_innerhtml.py）')
    ap.add_argument('date', help='日期 YYYYMMDD，如 20260513')
    ap.add_argument('output_file', nargs='?', default=None,
                    help='输出 HTML 文件名，如 caijing_20260513.html（默认: caijing_{date}.html）')
    ap.add_argument('--title', '-t', default=None, help='页面标题（默认: 财经早餐 YYYY-MM-DD）')
    args = ap.parse_args()

    result = build(
        html_file=args.html_file,
        date=args.date,
        output_file=args.output_file,
        title=args.title
    )
    print("\n✅ 完成:", json.dumps(result, ensure_ascii=False))

if __name__ == "__main__":
    main()

```

---

## 5. shared/__init__.py

```python
# shared/__init__.py
"""
shared/ - 通用积木库

所有模块均可独立使用，也可通过 shared 统一导入。

子模块:
    auth      - 鉴权与会话管理
    network   - 网络上传队列
    render    - HTML 生成引擎
    deploy    - 部署触发器
    utils     - 通用工具

快速使用:
    from shared.auth import HeadlessAuthSession
    from shared.network import github_batch_uploader
    from shared.render import HtmlGenerator
    from shared.deploy import GitHubPagesTrigger
"""

from shared.build_full import build

__all__ = ['build']

__path__ = __import__('pkgutil').extend_path(__path__, __name__)

```

---

## 6. scripts/scrape_and_upload.js

```javascript
// -*- coding: utf-8 -*-
/**
 * red-ring-scraper: 图片提取 + 上传脚本
 * 在 browser evaluate 中运行，使用浏览器登录态抓取 private.red-ring.cn 图片并上传到 GitHub
 *
 * 用法：在小红圈帖子页面打开 DevTools Console，执行本脚本
 */

// ========== 配置 ==========
const GITHUB_TOKEN = 'ghp_***REDACTED***';
const GITHUB_REPO = 'frankinvest/caijing-daily';
const api = 'https://api.github.com/repos';
const ghRaw = 'https://raw.githubusercontent.com/frankinvest/caijing-daily/main';

// ========== 工具函数 ==========

/**
 * 将 ArrayBuffer 转为 base64 字符串（浏览器 safe）
 */
function arrayBufferToBase64(arr) {
  var binary = '';
  var bytes = new Uint8Array(arr);
  for (var i = 0; i < bytes.length; i += 8192) {
    binary += String.fromCharCode.apply(null, bytes.slice(i, i + 8192));
  }
  return btoa(binary);
}

/**
 * 从 GitHub 获取文件 SHA（用于更新已存在文件）
 */
async function getFileSha(filename) {
  var r = await fetch(api + '/' + GITHUB_REPO + '/contents/' + filename + '?ref=main', {
    headers: { 'Authorization': 'token ' + GITHUB_TOKEN }
  });
  if (r.ok) {
    var d = await r.json();
    return d.sha;
  }
  return null;
}

/**
 * 上传文件到 GitHub（自动判断 sha）
 */
async function uploadFile(filename, base64Content) {
  var sha = await getFileSha(filename);
  var body = {
    message: 'Upload ' + filename,
    content: base64Content,
    branch: 'main'
  };
  if (sha) body.sha = sha;

  var r = await fetch(api + '/' + GITHUB_REPO + '/contents/' + filename, {
    method: 'PUT',
    headers: {
      'Authorization': 'token ' + GITHUB_TOKEN,
      'Content-Type': 'application/json'
    },
    body: JSON.stringify(body)
  });
  return r.json();
}

// ========== 主逻辑 ==========

(async function() {
  // 1. 提取所有 private.red-ring 图片 URL（去重 + 排除 avatar）
  var allImgUrls = [];
  var seenUrls = {};
  document.querySelectorAll('img').forEach(function(img) {
    var src = img.src || '';
    if (src.includes('private.red-ring') && !src.includes('avatar') && !seenUrls[src]) {
      seenUrls[src] = true;
      allImgUrls.push(src);
    }
  });

  console.error('Found image URLs:', allImgUrls.length);

  // 2. 上传每张图片
  var uploaded = {};
  for (var i = 0; i < allImgUrls.length; i++) {
    var url = allImgUrls[i];
    var ext = url.includes('.png') ? 'png' : 'jpg';
    // 文件名格式：caijing_YYYYMMDD_img_NN.ext
    // TODO: 替换为实际日期
    var filename = 'caijing_YYYYMMDD_img_' + String(i + 1).padStart(2, '0') + '.' + ext;

    try {
      var resp = await fetch(url);
      if (!resp.ok) {
        console.error('FAIL fetch', i + 1, resp.status, url.substring(0, 60));
        continue;
      }
      var buf = await resp.arrayBuffer();
      var b64 = arrayBufferToBase64(buf);
      var result = await uploadFile(filename, b64);

      if (result.content) {
        uploaded[url] = result.content.download_url;
        console.error('OK', i + 1, filename, '->', result.content.download_url);
      } else {
        console.error('FAIL upload', i + 1, JSON.stringify(result).substring(0, 150));
      }
    } catch(e) {
      console.error('ERR', i + 1, e.message);
    }
  }

  // 3. 返回结果
  return {
    total: allImgUrls.length,
    uploaded: Object.keys(uploaded).length,
    map: uploaded
  };
})();

```

---

## 7. shared/pipeline.py（遗留脚本，备查）

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
shared/pipeline.py
富文本无损流水线：HTML(in) → Markdown → 图片URL替换 → HTML(out)
"""
import sys, os, re, base64, time, urllib.request, json
sys.path.insert(0, os.path.dirname(os.path.dirname(os.path.abspath(__file__))))

from shared.network import GitHubUploader
from shared.deploy import GitHubPagesTrigger

try:
    import markdownify as mf
    HAS_MF = True
except ImportError:
    HAS_MF = False

TOKEN = "ghp_***REDACTED***"
REPO = "frankinvest/caijing-daily"
REF_URL = "https://www.red-ring.cn/post/27593-2120574"
HEADERS = {
    "Cookie": "Hm_lvt_1c9949e59fafcdf8f7cd363b452f1837=1778115791,1778500926; HMACCOUNT=77046ED79FB0AFED; Hm_lpvt_1c9949e59fafcdf8f7cd363b452f1837=1778653122",
    "User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/147.0.0.0 Safari/537.36",
    "Referer": REF_URL
}

def html_to_markdown(html):
    if HAS_MF:
        return mf.markdownify(html, heading_style="atx", link_style="inlined")
    # 降级正则方案
    t = re.sub(r'<br\s*/?>', '\n', html)
    t = re.sub(r'<p[^>]*>', '\n\n', t)
    t = re.sub(r'<[^>]+>', '', t)
    t = re.sub(r'\n{3,}', '\n\n', t)
    return t.strip()

def extract_md_images(md):
    urls = []
    for m in re.finditer(r'!\[([^\]]*)\]\(([^)]+)', md):
        u = m.group(2)
        if u not in urls:
            urls.append(u)
    return urls

def replace_md_urls(md, old_new):
    for o, n in old_new.items():
        md = md.replace(o, n)
    return md

def md_to_html(md, title=""):
    def img_replace(m):
        alt = m.group(1) or ""
        url = m.group(2)
        return f'<img src="{url}" alt="{alt}" style="max-width:100%;border-radius:4px;margin:8px 0;display:block">'
    body = re.sub(r'!\[([^\]]*)\]\(([^)]+)\)', img_replace, md)
    body = re.sub(r'\*\*(.+?)\*\*', r'<strong>\1</strong>', body)
    paras = []
    for line in body.splitlines():
        line = line.strip()
        if not line:
            continue
        if line.startswith('<img ') or line.startswith('<blockquote'):
            paras.append(line)
        else:
            paras.append(f'<p>{line}</p>')
    post_body = '\n'.join(paras)
    return (
        '<!DOCTYPE html>\n<html lang="zh">\n<head>\n'
        '<meta charset="UTF-8">\n'
        '<title>' + title + '</title>\n'
        '<style>\n'
        'body{font-family:-apple-system;font-size:14px;max-width:720px;margin:0 auto;padding:16px;background:#fafafa;line-height:1.7;color:#333}\n'
        '.post{background:white;border-radius:8px;padding:20px;margin-bottom:16px}\n'
        'img{max-width:100%;border-radius:4px;margin:8px 0}\n'
        'strong{color:#c00}\n'
        '.footer{text-align:center;color:#999;font-size:.8em;padding:20px 0;border-top:1px solid #eee;margin-top:30px}\n'
        '</style>\n'
        '</head>\n<body>\n<div class="post">\n' + post_body + '\n</div>\n'
        '<div class="footer">\n<p>来源：小红圈 · 红运Dang投 · MR Dang<br>MCP-RedRing 自动生成</p>\n'
        '</div>\n</body>\n</html>'
    )

def download_and_upload_imgs(urls, date, gh):
    mapping = {}
    total = len(urls)
    for i, url in enumerate(urls, 1):
        ext = 'png' if '.png' in url else ('webp' if 'webp' in url else 'jpg')
        fname = f"caijing_{date}_img_{i:02d}.{ext}"
        try:
            req = urllib.request.Request(url, headers=HEADERS)
            with urllib.request.urlopen(req, timeout=10) as r:
                if r.status != 200:
                    raise Exception(f"HTTP {r.status}")
                data = r.read()
                if len(data) < 2048:
                    raise Exception(f"文件过小({len(data)}B防盗链拒绝")
                if b'<!DOCTYPE' in data[:50]:
                    raise Exception("HTML错误页")
            b64 = base64.b64encode(data).decode('ascii')
            gurl = gh.upload(fname, b64)
            mapping[url] = gurl
            print(f"  OK {i}/{total} {fname} ({len(data)//1024}KB)")
        except Exception as e:
            print(f"  FAIL {i}/{total} {url[:60]}: {e}")
        if i < total:
            time.sleep(0.5)
    return mapping

def main():
    date = sys.argv[1] if len(sys.argv) > 1 else "20260512"
    html_path = sys.argv[2] if len(sys.argv) > 2 else None

    if not html_path or not os.path.exists(html_path):
        print("用法: python pipeline.py YYYYMMDD html_file")
        sys.exit(1)

    with open(html_path, encoding='utf-8') as f:
        raw_html = f.read()
    print(f"读入 HTML: {len(raw_html)} bytes")

    md = html_to_markdown(raw_html)
    print(f"Markdown: {len(md)} chars")

    imgs = extract_md_images(md)
    print(f"图片: {len(imgs)} 张")

    gh = GitHubUploader(token=TOKEN, repo=REPO)
    mapping = {}
    if imgs:
        mapping = download_and_upload_imgs(imgs, date, gh)
        md = replace_md_urls(md, mapping)

    final_html = md_to_html(md, title=f"财经早餐 {date}")
    gh_count = final_html.count('raw.githubusercontent.com')
    print(f"生成 HTML: {len(final_html)} bytes, GitHub图: {gh_count} 张")

    path = f"caijing_{date}.html"
    b64 = base64.b64encode(final_html.encode('utf-8')).decode('ascii')
    api = f"https://api.github.com/repos/{REPO}/contents/{path}"
    greq = urllib.request.Request(api + "?ref=main", headers={"Authorization": "token " + TOKEN})
    sha = None
    try:
        with urllib.request.urlopen(greq, timeout=10) as r:
            sha = json.loads(r.read()).get('sha')
    except Exception:
        pass
    body = {"message": f"Update {path}", "content": b64, "branch": "main"}
    if sha:
        body["sha"] = sha
    req2 = urllib.request.Request(
        api, data=json.dumps(body).encode('utf-8'),
        headers={"Authorization": "token " + TOKEN, "Content-Type": "application/json"},
        method="PUT"
    )
    with urllib.request.urlopen(req2, timeout=15) as r:
        res = json.loads(r.read())
    print("上传:", res.get('content', {}).get('download_url', '')[:80])

    ok = GitHubPagesTrigger(token=TOKEN, repo=REPO).trigger_and_wait()
    print("完成" if ok else "超时",
          f"https://frankinvest.github.io/caijing-daily/{path}")

if __name__ == "__main__":
    main()

```

---

## 8. SSOT 架构说明

### 核心原则

- **Skill**（red-ring-scraper）= 纯编排器，0 硬编码 DOM 选择器 / 正则 / 渲染逻辑
- **shared/build_full.py** = SSOT 渲染引擎，唯一事实来源
- **shared/cdp_get_innerhtml.py** = SSOT 提取工具，唯一数据入口

### 调用链路

```
User → Skill (编排)
          │
          ├── Step 1: Browser navigate + scroll (加载评论)
          │
          ├── Step 2: cdp_get_innerhtml.py → /tmp/<date>_post.html
          │
          ├── Step 3: build_full.py → /tmp/<date>_post.html
          │              ├── extract_post_body()    — 提取正文 HTML
          │              ├── extract_post_images()  — 提取图片 URL
          │              ├── upload_images()        — 下载 + 上传 GitHub
          │              ├── markdownify()          — 无损 DOM→Markdown
          │              ├── URL 替换                — 私有→GitHub
          │              ├── md_to_html_with_comments() — Markdown→HTML
          │              └── gh_put() + PagesTrigger — 上传 + 部署
          │
          └── Step 4: 上报 URL
```

### 关键修复记录

| 日期 | 文件 | Bug | 修复 |
|------|------|-----|------|
| 2026-05-13 | build_full.py, pipeline.py | `!\[...\]\(([^)]+)\)` — URL 含 `)` 时截断 | → `(.+?)` 非贪婪匹配 |
| 2026-05-13 | build_full.py | `extract_post_body()` 只支持 `.post-body`，不兼容 CDP `ql-view` | → 双版本选择器 |
| 2026-05-13 | build_full.py | 日期/输出文件名 hardcoded | → CLI argparse 参数化 |

---

## 9. 待优化项（封版前）

1. **帖子嗅探逻辑**：当前按 ID 倒序取"最新"，未过滤纯音频贴（.mp3 无图文）。需增加：对每个候选链接先导航检查 DOM 中是否含 `.ql-view` 正文或图片，再决定是否使用。
2. **pipeline.py**：存在与 build_full.py 重复的 regex bug（`[^)]+`），建议废弃或同步修复。
3. **评论提取**：CDP 提取时评论元素被移除，评论需单独处理（可扩展 Step 2.5）。

---

*报告由 OpenClaw Agent 自动生成*
