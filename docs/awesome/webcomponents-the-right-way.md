<div class="github-widget" data-repo="mateusortiz/webcomponents-the-right-way"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精选的 Web 组件资源精选列表.

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) — 一套不同的技术，允许您创建可重用的自定义元素 — 将它们的功能封装在您的代码的其余部分之外 — 并在您的 Web 应用程序中使用它们.



&gt; Web Components the Right Way 是由 [Mateus Ortiz](https://twitter.com/mteusortiz) 并由 [Serhii Kulykov](https://twitter.com/serhiikulykov)

## Introduction

- [Web Components 101](https://nhswd.com/blog/web-components-101-what-are-web-components/)
- [Intro to Web Components](https://developer.salesforce.com/blogs/2020/01/intro-to-web-components.html)
- [MDN - Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)

## Standards

### Custom Elements

自定义元素为作者提供了一种构建他们自己的全功能 DOM 元素的方法.

- [HTML Living Standard: Custom elements](https://html.spec.whatwg.org/multipage/custom-elements.html)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Handy Custom Elements' Patterns](https://gist.github.com/WebReflection/ec9f6687842aa385477c4afca625bbf4)
- [MDN - Using Custom Elements](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements)

### Shadow DOM

Shadow DOM 描述了一种将多个 DOM 树组合成一个层次结构的方法，以及这些树如何在文档中相互交互，从而实现更好的 DOM 组合.

- [DOM Living Standard: Interface `ShadowRoot`](https://dom.spec.whatwg.org/#interface-shadowroot)
- [DOM Living Standard: Shadow tree](https://dom.spec.whatwg.org/#shadow-trees)
- [MDN - Using Shadow DOM](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
- [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)
- [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth)
- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [Understanding Slot Updates with Web Components](https://coryrylan.com/blog/understanding-slot-updates-with-web-components)
- [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom)

### HTML Templates

 `<template>  ` 元素用于声明可以通过脚本克隆和插入文档的 HTML 片段.

- [HTML Living Standard: The `template` element](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
- [MDN - &lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [MDN - Using templates and slots](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/html/semantics/scripting-1/the-template-element)

### CSS Shadow Parts

CSS Shadow Parts 允许开发人员出于样式目的公开 Shadow DOM 中的某些元素.

- [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
- [CSS Shadow Parts are coming!](https://dev.to/webpadawan/css-shadow-parts-are-coming-mi5)
- [MDN - `::part()` CSS pseudo element](https://developer.mozilla.org/en-US/docs/Web/CSS/::part)
- [MDN - `part` global attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/part)
- [::part and ::theme, an ::explainer](https://meowni.ca/posts/part-theme-explainer/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts)

### Polyfills

### Custom Elements polyfills

- [@webcomponents/custom-elements](https://github.com/webcomponents/polyfills/tree/master/packages/custom-elements) - Polymer 团队的自定义元素 polyfill.
- [document-register-element](https://github.com/WebReflection/document-register-element) - Andrea Giammarchi 的自定义元素 polyfill.

### Customized Built-in Elements polyfills

- [@corpuscule/custom-builtin-elements](https://github.com/corpusculejs/custom-builtin-elements) - 自定义的内置元素 polyfill by [CorpusculeJS](https://github.com/corpusculejs).
- [@ungap/custom-elements-builtin](https://github.com/ungap/custom-elements-builtin) - 自定义的内置元素 polyfill by [ungap project](https://ungap.github.io).

### Shadow DOM shims

- [@webcomponents/shadydom](https://github.com/webcomponents/polyfills/tree/master/packages/shadydom) - ShadowDOM v1 垫片.
- [@webcomponents/shadycss](https://github.com/webcomponents/polyfills/tree/master/packages/shadycss) - ShadowDOM 风格的封装垫片.
- [@lwc/synthetic-shadow](https://github.com/salesforce/lwc/blob/master/packages/@lwc/synthetic-shadow) - Shadow DOM polyfill by [LWC](https://lwc.dev).

### HTML Templates polyfills

- [@webcomponents/template](https://github.com/webcomponents/polyfills/tree/master/packages/template)  - 最小的polyfill`<template>  `.
- [@ungap/import-node](https://github.com/ungap/import-node) - IE11 的`importNode` polyfill by [ungap project](https://ungap.github.io).

## Guides

### Accessibility

- [Accessibility for Web Components](https://developer.salesforce.com/blogs/2020/01/accessibility-for-web-components.html)
- [How to Make Accessible Web Components — a Brief Guide](https://www.sitepoint.com/accessible-web-components/)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [The Guide to Accessible Web Components](https://www.erikkroes.nl/blog/accessibility/the-guide-to-accessible-web-components-draft/)
- [Web Components and the Accessibility Object model (AOM)](https://www.24a11y.com/2019/web-components-and-the-aom/)
- [Web Components punch list](https://www.tpgi.com/web-components-punch-list/)
- [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

### Best Practices

- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [Developing Components: Publishing](https://open-wc.org/guides/developing-components/publishing/)
- [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
- [How to Publish Web Components to NPM](https://justinfagnani.com/2019/11/01/how-to-publish-web-components-to-npm/)
- [Open Web Components Recommendations](https://open-wc.org)

### Codelabs

- [Build a Story Web Component with LitElement](https://dev.to/straversi/build-a-story-web-component-with-litelement-e59)
- [Building Custom Elements with Web Components for the 2020 Elections](https://medium.com/stories-from-upstatement/building-custom-elements-with-web-components-for-the-2020-elections-f767ff9e9c6a)
- [Building Web Components with Vanilla JavaScript](https://dev.to/aspittel/building-web-components-with-vanilla-javascript--jho)
- [Creating a Reusable Avatar Web Component](https://marcoslooten.com/blog/creating-a-reusable-avatar-web-component/)
- [Creating Web Components with Stencil](https://auth0.com/blog/creating-web-components-with-stencil/)
- [From Web Component to Lit Element](https://codelabs.developers.google.com/codelabs/the-lit-path)
- [Getting started with LitElement and TypeScript](https://labs.thisdot.co/blog/getting-started-with-litelement-and-typescript)
- [Handling data with Web Components](https://itnext.io/handling-data-with-web-components-9e7e4a452e6e)
- [How to use D3js with WebComponents](https://towardsdatascience.com/how-to-use-d3js-with-webcomponents-a75ae4f980de)
- [Introduction to Storybook for Web Components](https://sinhapiyush.hashnode.dev/introduction-to-storybook-for-web-components)
- [Navigation Lifecycle using Vaadin Router, LitElement and TypeScript](https://labs.thisdot.co/blog/navigation-lifecycle-using-vaadin-router-litelement-and-typescript)
- [Open Web Components: Codelabs](https://open-wc.org/guides/developing-components/codelabs/)
- [Recreating The Arduino Pushbutton Using SVG And `<lit-element>`](https://www.smashingmagazine.com/2020/01/recreating-arduino-pushbutton-svg/)
- [Routing Management with LitElement and TypeScript](https://labs.thisdot.co/blog/routing-management-with-litelement)
- [Snake-Eating Game Making with Web Components of Omi and MVP Architecture](https://dev.to/dntzhang/snake-eating-game-making-with-web-components-of-omi-and-mvp-architecture-206)
- [Storybook for web components on steroids](https://dev.to/open-wc/storybook-for-web-components-on-steroids-4h29)
- [Testing Workflow for Web Components](https://dev.to/open-wc/testing-workflow-for-web-components-g73)
- [Web Components Tools: A Comparison](https://www.nexmo.com/blog/2020/05/20/web-components-tools-a-comparison)

### Examples

- [generic-components](https://github.com/thepassle/generic-components) - 通用 Web 组件的集合，重点是可访问性和易用性.
- [howto-components](https://github.com/GoogleChromeLabs/howto-components) - 实现常见 Web UI 模式的 Web 组件的集合.
- [open-wc code examples](https://open-wc.org/guides/developing-components/code-examples/) - 用于开发 Web 组件的最佳实践和设计模式的集合.
- [vanilla-retro-js](https://github.com/martine-dowden/vanilla-retro-js) - 不推荐使用的 HTML 标签的 Vanilla JS UI 组件库.
- [web-components-examples](https://github.com/mdn/web-components-examples) - 一系列 Web 组件示例，与 MDN Web 组件文档相关.

## Articles

### Architecture

- [A deep analysis into isomorphic, autonomous cross-framework usage #MicroFrontends](https://itnext.io/a-deep-analysis-into-isomorphic-autonomous-cross-framework-usage-microfrontends-364271dc5fa9)
- [Frankenstein Migration: Framework-Agnostic Approach (Part 1)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-1/)
- [Frankenstein Migration: Framework-Agnostic Approach (Part 2)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-2/)
- [Generating Config driven Dynamic Forms using Web Components](https://codeburst.io/generating-config-driven-dynamic-forms-using-web-components-7c8d400f7f2e)
- [Hiding internal framework methods and properties from web component APIs](https://component.kitchen/blog/posts/hiding-internal-framework-methods-and-properties-from-web-component-apis)
- [How to deliver Custom Elements](https://medium.com/@WebReflection/how-to-deliver-custom-elements-702fae32d25c)
- [Making Web Components for Different Contexts](https://css-tricks.com/making-web-components-for-different-contexts/)
- [Supporting both automatic and manual registration of custom elements](https://component.kitchen/blog/posts/supporting-both-automatic-and-manual-registration-of-custom-elements)
- [Web Components — the right way](https://equinusocio.dev/blog/web-components-the-right-way/)

### Interoperability

- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)
- [Web Components aren't a framework replacement - they're better than that](https://lamplightdev.com/blog/2020/01/18/web-components-arent-a-framework-replacement-theyre-better-than-that/)
- [Web Components: Seamlessly interoperable](https://medium.com/@sergicontre/web-components-seamlessly-interoperable-82efd6989ca4)

### Limitations

- [Beyond the polyfills: how Web Components affect us today?](https://dev.to/webpadawan/beyond-the-polyfills-how-web-components-affect-us-today-3j0a)
- [Custom elements, shadow DOM and implicit form submission](https://www.hjorthhansen.dev/shadow-dom-and-forms/)
- [Form-associated custom elements](https://www.hjorthhansen.dev/shadow-dom-form-participation/)
- [You might not need shadow DOM](https://www.hjorthhansen.dev/you-might-not-need-shadow-dom/)

### Styling

- [Options for styling web components](https://nolanlawson.com/2021/01/03/options-for-styling-web-components/)
- [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
- [Styling in the Shadow DOM With CSS Shadow Parts](https://css-tricks.com/styling-in-the-shadow-dom-with-css-shadow-parts/)
- [Styling is critical to web component reuse, but may prove difficult in practice](https://component.kitchen/blog/posts/styling-is-critical-to-web-component-reuse-but-may-prove-difficult-in-practice)
- [Thinking Through Styling Options for Web Components](https://css-tricks.com/thinking-through-styling-options-for-web-components/)
- [Web Standards Meet User-Land: Using CSS-in-JS to Style Custom Elements](https://css-tricks.com/web-standards-meet-user-land-using-css-in-js-to-style-custom-elements/)

## Real World

### Case Studies

- [Apple Just Shipped Web Components to Production and You Probably Missed It](https://dev.to/ionic/apple-just-shipped-web-components-to-production-and-you-probably-missed-it-57pf)
- [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
- [Get moving with Microsoft’s FAST web components](https://www.infoworld.com/article/3618410/get-moving-with-microsofts-fast-web-components.html)
- [How Web Components Are Used at GitHub and Salesforce](https://thenewstack.io/how-web-components-are-used-at-github-and-salesforce/)
- [How we use Web Components at GitHub](https://github.blog/2021-05-04-how-we-use-web-components-at-github/)
- [Implementing a Design Language System with Stencil.js](https://medium.com/@Danetag/implementing-a-design-language-system-with-stencil-js-515432918eb5)
- [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
- [ING Open-Sources Lion, Its White-Label Web Component Library – Q&A with Thomas Allmer](https://www.infoq.com/articles/ing-open-sources-lion-web-component/)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
- [Looking back on five years of web components](https://bitworking.org/news/2019/07/looking-back-on-five-years-of-web-components)
- [Shipping Web Components in 2020](https://dev.to/joe8bit/shipping-web-components-in-2020-2h54)
- [The Firefox UI is now built with Web Components](https://briangrinstead.com/blog/firefox-webcomponents/)
- [Using web components to encapsulate CSS and resolve design system conflicts](https://about.gitlab.com/blog/2021/05/03/using-web-components-to-encapsulate-css-and-resolve-design-system-conflicts/)
- [Web Components at GitHub - Web Components SF Meetup](https://www.infoq.com/news/2020/08/web-components-sf-meetup-2020/)
- [Web Components at Scale at Salesforce: Challenges Encountered, Lessons Learnt](https://www.infoq.com/news/2020/03/web-components-salesforce-lwc/)
- [Web Development At Scale: Composable Applications With Web Components](https://medium.com/@jarrodek/composable-applications-with-web-components-ebe5158387be)
- [web.dev engineering blog #1: How we build the site and use Web Components](https://web.dev/how-we-build-webdev-and-use-web-components/)

### Components

- [`<api-viewer>`](https://github.com/web-padawan/api-viewer-element) - Web 组件的 API 文档和现场操场.
- [`<chess-board>`](https://github.com/justinfagnani/chessboard-element) - 独立的棋盘网络组件.
- [`<css-doodle>`](https://github.com/css-doodle/css-doodle) - 使用 CSS 绘制图案的 Web 组件.
- [`<dark-mode-toggle>`](https://github.com/GoogleChromeLabs/dark-mode-toggle) - 允许创建暗模式切换或开关的自定义元素.
- [`<emoji-picker>`](https://github.com/nolanlawson/emoji-picker-element) - 轻量级表情符号选择器，作为 Web 组件分发.
- [`<fg-modal>`](https://github.com/filamentgroup/fg-modal) - 可访问的模态对话框 Web 组件.
- [`<file-viewer>`](https://github.com/avipunes/file-viewer) - 使用 Svelte 构建的用于查看文件的 Web 组件.
- [`<json-viewer>`](https://github.com/alenaksu/json-viewer) - 在树视图中可视化 JSON 数据的 Web 组件.
- [`<lite-youtube>`](https://github.com/paulirish/lite-youtube-embed) - 精简版 YouTube 嵌入，专注于视觉表现.
- [`<midi-player>`](https://github.com/cifkao/html-midi-player) - MIDI 文件播放器和可视化器 Web 组件.
- [`<model-viewer>`](https://github.com/google/model-viewer) - Web component for rendering interactive 3D models.
- [`<player-x>`](https://github.com/playerxo/playerx) - 媒体播放器网络组件.
- [`<progressive-image>`](https://github.com/andreruffert/progressive-image-element) - 自定义元素以逐步增强图像占位符.
- [`<range-slider>`](https://github.com/andreruffert/range-slider-element) - 具有键盘支持的可访问范围滑块自定义元素.
- [`<rapi-doc>`](https://github.com/mrin9/RapiDoc) - 用于从 OpenAPI 规范创建文档的 Web 组件.
- [`<shader-doodle>`](https://github.com/halvves/shader-doodle) - 用于编写和渲染着色器的 Web 组件.
- [`<trix-editor>`](https://github.com/basecamp/trix) - 用于日常写作的富文本编辑器自定义元素.
- [`<vime-player>`](https://github.com/vime-js/vime) - 可定制、可扩展、可访问且与框架无关的媒体播放器.
- [`<web-vitals>`](https://github.com/stefanjudis/web-vitals-element) - 带来 [web vitals](https://github.com/GoogleChrome/web-vitals) 使用自定义元素快速进入您的页面.

### Component Libraries

- [AMP](https://github.com/ampproject/amphtml) - 用于轻松创建用户至上的网站、故事、广告、电子邮件等的 Web 组件框架.
- [Apollo Elements](https://github.com/apollo-elements/apollo-elements) - 用于将 Apollo GraphQL 与各种 Web 组件库结合使用的自定义元素.
- [AXA Pattern Library](https://github.com/axa-ch/patterns-library) - 使用 Web 组件构建的 AXA CH UI 组件库.
- [Blackstone UI](https://github.com/kjantzer/bui) - Web components for creating interfaces by Blackstone Publishing.
- [Blaze UI Atoms](https://github.com/BlazeSoftware/atoms) - 由 Blaze CSS 提供支持的一组 Web 组件.
- [Brightspace UI core](https://github.com/BrightspaceUI/core) - 用于构建 Brightspace 应用程序的 Web 组件集合.
- [Clever components](https://github.com/CleverCloud/clever-components) - 由 Clever Cloud 制作的 Web 组件集合.
- [DataFormsJS](https://github.com/dataformsjs/dataformsjs) - 用于 SPA 路由、显示来自 Web 服务的数据等的独立组件.
- [elements-sk](https://github.com/google/elements-sk) - 用于“点菜”网络开发的自定义元素集合.
- [github-elements](https://github.com/github/github-elements) - GitHub 的 Web 组件集合.
- [Elix](https://github.com/elix/elix) - 用于常见用户界面模式的高质量、可定制的 Web 组件.
- [Immersive Custom Elements](https://github.com/MozillaReality/immersive-custom-elements) - 用于嵌入沉浸式（VR 和 AR）内容的 Web 组件集.
- [Iooxa](https://github.com/iooxa/article) - 用于交互式科学写作、反应性文档和可探索性解释的 Web 组件.
- [Joomla UI custom elements](https://github.com/joomla-projects/custom-elements) - Joomla 4 自定义元素的编译.
- [Ketch.UP](https://github.com/smeup/ketchup) - Sme.UP 的 Web 组件库.
- [Lion Web Components](https://github.com/ing-bank/lion) - 一组高性能、可访问且灵活的 Web 组件.
- [LRNWebComponents](https://github.com/elmsln/lrnwebcomponents/) - ELMS:LN 为任何项目生成 Web 组件.
- [Lume](https://github.com/lume/lume) - 用于定义使用 CSS3D 或 WebGL 渲染的 2D 或 3D 场景的自定义元素.
- [Microsoft Graph Toolkit](https://github.com/microsoftgraph/microsoft-graph-toolkit) - Microsoft Graph 的 Web 组件集合.
- [Nightingale](https://github.com/ebi-webcomponents/nightingale) - 生命科学的数据可视化网络组件.
- [Nuxeo Elements](https://github.com/nuxeo/nuxeo-elements) - 使用 Web Components 使用 Nuxeo 构建 Web 应用程序的组件.
- [Open Business Application Platform Web Components](https://github.com/openbap/obap-elements) - 为业务应用程序设计的 Web 组件集合.
- [Pixano Elements](https://github.com/pixano/pixano-elements) - 专用于数据注释任务的可重复使用的 Web 组件.
- [Shoelace](https://github.com/shoelace-style/shoelace) - 具有前瞻性的 Web 组件库.
- [Smart Web Components](https://github.com/HTMLElements/smart-webcomponents) - 用于业务应用程序的 Web 组件.
- [TEI Publisher Components](https://github.com/eeditiones/tei-publisher-components) - TEI Publisher 使用的 Web 组件及其生成的应用程序的集合.
- [Tradeshift Elements](https://github.com/Tradeshift/elements) - 可重用的 Tradeshift UI 组件作为 Web 组件.
- [Vaadin components](https://github.com/vaadin/web-components) - 不断发展的高质量 Web 组件集，用于构建业务 Web 应用程序.
- [Warp View](https://github.com/senx/warpview) - 用于 Warp 10 的图表 Web 组件的集合.
- [Wired Elements](https://github.com/wiredjs/wired-elements) - 一组具有手绘粗略外观的常见 UI 元素.
- [Wokwi Elements](https://github.com/wokwi/wokwi-elements) - Arduino 和各种电子部件的 Web 组件.
- [XWeather](https://github.com/kherrick/x-weather) - 实现 OpenWeatherMap API 部分的 Web 组件的集合.

### Design Systems

- [Amber Components](https://github.com/bitrockteam/amber-components) - Amber 设计系统的 Web 组件实现.
- [Bolt Design System](https://github.com/boltdesignsystem/bolt) - 由 Twig 和 Web 组件驱动的 UI 组件、可重用的视觉样式和工具.
- [Calcite Components](https://github.com/Esri/calcite-components) - 用于 Esri 的 Calcite 设计框架的共享 Web 组件.
- [Carbon Custom Elements](https://github.com/carbon-design-system/carbon-custom-elements) - 基于 Web 组件的碳设计系统变体.
- [Chameleon Web Components](https://github.com/MaritzSTL/chameleon) - 基于变色龙设计系统的与框架无关的元素的集合.
- [Clarity Core Web Components](https://github.com/vmware/clarity/tree/master/packages/core) - 来自 Clarity Design System 的 Web 组件套件.
- [Crayons](https://github.com/freshdesk/crayons) - 遵循 Freshworks 设计系统的 Web 组件集合.
- [FAST Components](https://github.com/microsoft/fast/tree/master/packages/web-components/fast-components) - 基于 FAST 设计语言的 Web 组件库.
- [Fluent UI Web Components](https://github.com/microsoft/fluentui/tree/master/packages/web-components) - 支持 Microsoft 的 Fluent 设计语言的 Web 组件库.
- [GOV.UK Web Components](https://github.com/tgreyuk/govuk-webcomponents) - 一组使用 GOV.UK 设计系统的封装 Web 组件.
- [Helix UI](https://github.com/HelixDesignSystem/helix-ui) - Helix 设计系统的 Web 组件库.
- [Lyne Components](https://github.com/lyne-design-system/lyne-components) - Lyne 设计系统的构建块基于 Web 组件.
- [Material Web Components](https://github.com/material-components/material-components-web-components) - Material Design 实现为 Web 组件.
- [NuML | NUDE Elements](https://github.com/tenphi/numl) - 基于 Web 组件和运行时 CSS 生成的 HTML 框架和设计系统.
- [PatternFly Elements](https://github.com/patternfly/patternfly-elements) - 基于统一设计工具包的灵活轻量级 Web 组件的集合.
- [Pearson Web Components](https://github.com/pearson-ux/web-components) - Pearson 的可共享组件库，实现了 Gravity 设计系统.
- [Spectrum Web Components](https://github.com/adobe/spectrum-web-components) - 使用 Web 组件构建的 Adob​​e Spectrum 设计语言实现.
- [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) - 一组可重用的 UI 元素，用于实施 SAP Fiori 设计指南.
- [U-M Library Design System](https://github.com/mlibrary/design-system) - 密歇根大学图书馆设计系统.
- [Zooplus web components](https://github.com/zooplus/zoo-web-components) - 一组实现 Z+ 商店风格指南的 Web 组件.

### Use Cases

- [How we chose to build our Design System using StencilJS Web Components](https://medium.com/8451/how-we-chose-to-build-our-design-system-using-stenciljs-web-components-4878c36743c5)
- [How searching for a bundle-free React led me to web components](https://www.bryanbraun.com/2020/08/31/how-searching-for-a-bundle-free-react-led-me-to-web-components/)
- [Reasons Web Components are perfect for a big company](https://medium.com/@sergicontre/reasons-web-components-are-perfect-for-a-big-company-28790d712ad5)
- [5 Reasons Web Components Are Perfect for Design Systems](https://ionicframework.com/blog/5-reasons-web-components-are-perfect-for-design-systems/)
- [Web components: the secret ingredient helping power the web](https://web.dev/web-components-io-2019/)
- [Web Components for Enterprise. Part 1: Salesforce, Oracle, SAP](https://dev.to/webpadawan/web-components-for-enterprise-part-1-salesforce-oracle-sap-e70)
- [Web Components for Enterprise. Part 2: Nuxeo, Ionic, Vaadin](https://dev.to/webpadawan/web-components-for-enterprise-part-2-nuxeo-ionic-vaadin-22l7)
- [Why I use Web Components - My use cases](https://dev.to/shihn/why-i-use-web-components-my-use-cases-1nip)
- [Why we use Web Components](https://viljamis.com/2019/why-we-use-web-components/) 经过 [@viljamis](https://twitter.com/viljamis)
- [Why we use Web Components](https://dev.to/ionic/why-we-use-web-components-2c1i) 经过 [@maxlynch](https://twitter.com/maxlynch)

## Libraries

### Class Based

- [Corpuscule](https://github.com/corpusculejs/corpuscule) - 基于装饰器的小型 Web 组件框架.
- [DNA](https://github.com/chialab/dna) - 渐进式 Web 组件库.
- [FAST Element](https://github.com/microsoft/fast/tree/master/packages/web-components/fast-element) - 用于构建高性能、内存高效、符合标准的 Web 组件的轻量级库.
- [LitElement](https://lit-element.polymer-project.org)  - 用于创建快速、轻量级 Web 组件的简单基类. 聚合物项目的一部分.
- [Lightning Web Components](https://github.com/salesforce/lwc) - 速度极快的企业级 Web 组件基础.
- [Omi](https://github.com/Tencent/omi) - 4kb JavaScript 中的下一代 Web 框架（Web 组件 + JSX + 代理 + 商店 + 路径更新）.
- [Panel](https://github.com/mixpanel/panel) - Web 组件 + 虚拟 DOM：强大 UI 的 Web 标准.
- [Polymer](https://polymer-library.polymer-project.org) - Polymer 项目作者的原始 Web 组件库.
- [Skate](https://github.com/skatejs/skatejs) - Web 组件库专注于功能渲染管道和较小的占用空间.
- [slim.js](https://github.com/slimjs/slim.js) - 基于现代标准的快速而强大的前端微框架.
- [Stencil](https://github.com/ionic-team/stencil) - 用于生成 Web 组件的编译器.
- [Tonic](https://github.com/optoolco/tonic) - 极简、稳定、审计友好的组件框架.

### Functional

- [atomico](https://github.com/atomicojs/atomico) - 使用函数和钩子基于 Web 组件创建接口的小型库.
- [fuco](https://github.com/wtnbass/fuco) - 像 React 这样的功能组件，但用于 Web 组件.
- [haunted](https://github.com/matthewp/haunted) - 为 Web 组件实现的 React 的 Hooks API.
- [hybrids](https://github.com/hybridsjs/hybrids) - 用于创建具有简单和功能 API 的 Web 组件的 UI 库.
- [Solid](https://github.com/ryansolid/solid) - 用于创建用户界面的声明性 JavaScript 库.

### Integrations

- [ember-custom-elements](https://github.com/Ravenstine/ember-custom-elements) - 使用自定义元素渲染 Ember 和 Glimmer 组件.
- [preact-custom-element](https://github.com/preactjs/preact-custom-element) - 从 preact 组件生成/注册自定义元素.
- [@adobe/react-webcomponent](https://github.com/adobe/react-webcomponent) - 在自定义元素中自动包装 React 组件.
- [react-shadow](https://github.com/Wildhoney/ReactShadow) - 在 React 中利用 Shadow DOM 以及样式封装的所有好处.
- [reactify-wc](https://github.com/BBKolton/reactify-wc) - 使用具有 React 属性和功能的 Web 组件.
- [remount](https://github.com/rstacruz/remount) - 使用自定义元素将 React 组件挂载到 DOM.
- [@riotjs/custom-elements](https://github.com/riot/custom-elements) - 使用 Riot.js 创建普通自定义元素的简单 API.

### Benchmarks

- [All the Ways to Make a Web Component](https://webcomponents.dev/blog/all-the-ways-to-make-a-web-component/)
- [web-components-benchmark](https://vogloblinsky.github.io/web-components-benchmark/) - 使用各种示例对 Web 组件技术进行基准测试.
- [web-components-todo](https://wc-todo.firebaseapp.com/) - 出于基准测试目的，在不同的 Web 组件库中构建了相同的待办事项应用程序.

## Frameworks

### Angular

- [Angular Elements Overview](https://angular.io/guide/elements)
- [Building and consuming Angular Elements as Web Components](https://indepth.dev/building-and-bundling-web-components/)
- [How to use Angular ngModel and ngForms with WebComponents](https://itnext.io/how-to-use-angular-ngmodel-and-ngforms-with-webcomponents-802bd9e1d3d7)
- [Using Web Components in Angular](https://coryrylan.com/blog/using-web-components-in-angular)
- [Web Components With Angular Ivy In 6 Steps](https://www.softwarearchitekt.at/post/2019/05/18/web-components-custom-elements-with-angular-ivy-in-6-steps.aspx)

### React

- [Rendering React Components With Custom Elements](https://guillaumebriday.fr/rendering-react-components-with-custom-elements)
- [How to use Web Components in React](https://www.robinwieruch.de/react-web-components)

### Vue

- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
- [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)
- [Integrate Web Components with Your Vue.js App](https://alligator.io/vuejs/vue-integrate-web-components/)
- [Using Web Components in Vue](https://coryrylan.com/blog/using-web-components-in-vue)

### Svelte

- [Svelte Custom Element API](https://svelte.dev/docs#Custom_element_API)
- [How to Create a Web Component in Svelte](https://dev.to/silvio/how-to-create-a-web-components-in-svelte-2g4j)
- [Svelte Web Component — 5.4KB](https://itnext.io/svelte-web-component-5-4kb-4afe46590d99)

## Ecosystem

### Starter Kits

- [Create Open Web Components](https://open-wc.org/docs/development/generator/) - Web 组件项目脚手架.
- [custom-element-boilerplate](https://github.com/github/custom-element-boilerplate) - 用于创建自定义元素的样板.
- [hello-web-components](https://github.com/fernandopasik/hello-web-components) - 用 TypeScript 编写的简单入门 hello world Web 组件.
- [nutmeg](https://github.com/abraham/nutmeg) - 构建、测试和发布带有一点趣味的普通 Web 组件.

### Tools

- [Backlight](https://backlight.dev/) — 以开发人员和设计人员之间的协作为核心，Backlight 是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统. 
- [Custom Elements Locator](https://github.com/open-wc/locator) - 用于在页面上查找自定义元素的 Chrome 扩展程序.
- [query-selector-shadow-dom](https://github.com/Georgegriff/query-selector-shadow-dom) - 可以穿透 Shadow DOM 根的 querySelector，对自动化测试很有用.
- [shadow-automation-selenium](https://github.com/sukgu/shadow-automation-selenium) - 使用 Selenium 的 Shadow DOM 自动化.
- [shadow-dom-utils](https://github.com/43081j/shadow-dom-utils) - 一组用于处理 shadow DOM 的有用实用程序，主要用于测试环境.
- [@storybook/web-components](https://www.npmjs.com/package/@storybook/web-components) - 用于纯 Web 组件片段的 UI 开发环境.
- [webcomponents.dev](https://webcomponents.dev) - 面向 Web 平台开发人员的组件 IDE.
- [web-component-analyzer](https://github.com/runem/web-component-analyzer) - 分析 Web 组件并发出文档/诊断信息的 CLI.
- [Web Components Codemods](https://github.com/kcmr/web-components-codemods) - Web 组件的 Codemods.

## Books

- [Web Components in Action](https://www.manning.com/books/web-components-in-action) - 由 Ben Farrell 预订，可在 Manning 早期发布计划中获得.
- [Web Component Essentials](https://leanpub.com/web-component-essentials) - 由 Cory Rylan 编写，Leanpub 提供早期预览版.

## Tutorials

- “**让我们构建 Web 组件！**”作者： [Benny Powers](https://github.com/bennypowers)
  - [Part 1: The Standards](https://dev.to/bennypowers/lets-build-web-components-part-1-the-standards-3e85)
  - [Part 2: The Polyfills](https://dev.to/bennypowers/lets-build-web-components-part-2-the-polyfills-dkh)
  - [Part 3: Vanilla Components](https://dev.to/bennypowers/lets-build-web-components-part-3-vanilla-components-4on3)
  - [Part 4: Polymer Library](https://dev.to/bennypowers/lets-build-web-components-part-4-polymer-library-4dk2)
  - [Part 5: LitElement](https://dev.to/bennypowers/lets-build-web-components-part-5-litelement-906)
  - [Part 6: Gluon](https://dev.to/bennypowers/lets-build-web-components-part-6-gluon-27ll)
  - [Part 7: Hybrids](https://dev.to/bennypowers/lets-build-web-components-part-7-hybrids-187l)

- &quot;**Web 组件：从零到英雄**&quot; by [Pascal Schilp](https://github.com/thepassle)
  - [Part 1: An introduction to writing raw Web Components](https://dev.to/thepassle/web-components-from-zero-to-hero-4n4m)
  - [Part 2: Supercharging Web Components with lit-html](https://dev.to/thepassle/web-components-from-zero-to-hero-part-two-38p4)
  - [Part 3: Web Components hero with LitElement](https://dev.to/thepassle/web-components-from-zero-to-hero-part-three-3c5h)

- “**现代 JavaScript 教程**”作者： [Ilya Kantor](https://github.com/iliakan)
  - [Part 1: From the orbital height](https://javascript.info/webcomponents-intro)
  - [Part 2: Custom Elements](https://javascript.info/custom-elements)
  - [Part 3: Shadow DOM](https://javascript.info/shadow-dom)
  - [Part 4: Template element](https://javascript.info/template-element)
  - [Part 5: Shadow DOM slots, composition](https://javascript.info/slots-composition)
  - [Part 6: Shadow DOM styling](https://javascript.info/shadow-dom-style)
  - [Part 7: Shadow DOM and events](https://javascript.info/shadow-dom-events)

-“**操作方法：组件**”作者： [Web Fundamentals](https://developers.google.com/web/fundamentals/)
  - [Overview](https://developers.google.com/web/fundamentals/web-components/examples)
  - [`<howto-checkbox>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-checkbox)
  - [`<howto-tabs>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-tabs)
  - [`<howto-tooltip>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-tooltip)

- **CSS 技巧** 文章系列作者 [Caleb Williams](https://css-tricks.com/author/calebdwilliams/)
  - [Part 1: An Introduction to Web Components](https://css-tricks.com/an-introduction-to-web-components/)
  - [Part 2: Crafting Reusable HTML Templates](https://css-tricks.com/crafting-reusable-html-templates/)
  - [Part 3: Creating a Custom Element from Scratch](https://css-tricks.com/creating-a-custom-element-from-scratch)
  - [Part 4: Encapsulating Style and Structure with Shadow DOM](https://css-tricks.com/encapsulating-style-and-structure-with-shadow-dom/)
  - [Part 5: Advanced Tooling for Web Components](https://css-tricks.com/advanced-tooling-for-web-components/)

- **Angular Elements** 文章系列 [Manfred Steyer](https://www.angulararchitects.io/about/)
  - [Part I: A Dynamic Dashboard In Four Steps With Web Components](https://www.angulararchitects.io/aktuelles/angular-elements-part-i/)
  - [Part II: Lazy and External Web Components](https://www.angulararchitects.io/aktuelles/angular-elements-part-ii/)
  - [Part III: Angular Elements Without Zone.Js](https://www.angulararchitects.io/aktuelles/angular-elements-part-iii/)
  - [Part IV: Content Projection with Slots in Angular Elements (>=7)](https://www.angulararchitects.io/aktuelles/content-projection-with-slots-in-angular-elements-7/)
  - [Part V: Your Options for Building Angular Elements with the CLI](https://www.angulararchitects.io/aktuelles/your-options-for-building-angular-elements/)

## Insights

### Podcasts

- [代码[ish]，第 38 集：使用 Web 组件构建](https://www.heroku.com/podcasts/codeish/38-building-with-web-components)
- [Frontend Happy Hour, episode 62: Web Components - shots of shadow DOM](https://frontendhappyhour.com/episodes/web-components-shots-of-shadow-dom/)
- [Labs Talk - Web Components with Peter Muessig](https://labstalk.buzzsprout.com/993481/3932975-web-components-with-peter-muessig)
- [Real Talk JavaScript, episode 7: Custom Web Components with Rob Wormald](https://realtalkjavascript.simplecast.fm/eaf3db9e)
- [Real Talk JavaScript, episode 101: Back to Basics with Native HTML and LitElement](https://realtalkjavascript.simplecast.com/episodes/episode-101-back-to-basics-with-native-html-and-litelement)

### Presentations

- [Are Web Components the Betamax of web development?](https://noti.st/lostinbrittany/EjUZyd/are-web-components-the-betamax-of-web-development) 经过 [@lostinbrittany](https://twitter.com/lostinbrittany)
- [Designing St和ard Systems](https://drive.google.com/file/d/1ALFiWOFU0UAGUpaZPMIVnoADs9_REtL5/view) 经过 [@stefsull](https://twitter.com/stefsull) 和 [@bferrua](https://twitter.com/bferrua)
- [Frontend Architecture for Scalable Design Systems](https://events.drupal.org/seattle2019/sessions/design-system-architecture-pattern-lab-twig-and-web-components) 经过 [@salem_cobalt](https://twitter.com/salem_cobalt)
- [lit-apollo: Data-Driven Components that Use the Platform](https://apolloelements.dev/using-lit-apollo/) 经过 [@PowersBenny](https://twitter.com/PowersBenny)
- [Mastering Shadow DOM](https://martine-dowden.github.io/portfolio/presentation/mastering-shadow-dom) 经过 [@Martine_Dowden](https://twitter.com/Martine_Dowden)
- [Modernizing Large Frontends with Web Components](https://speakerdeck.com/samjulien/modernizing-large-frontends-with-web-components) 经过 [@samjulien](https://twitter.com/samjulien)
- [Shadow DOM: off the beaten track](https://docs.google.com/presentation/d/1wi74YiTLtLSfgjyccKm5LxYp9k8aeJda0AekWV5mqJI/edit?usp=sharing) 经过 [@serhiikulykov](https://twitter.com/serhiikulykov)
- [Using Web Components to Build a Framework-agnostic UI Library](https://gotochgo.com/2019/sessions/866/using-web-components-to-build-a-framework-agnostic-ui-library) 经过 [@brianbouril](https://twitter.com/brianbouril) 和 [@danciupuliga](https://twitter.com/danciupuliga)
- [Web Components and the AOM](https://decks.tink.uk/2019/jsconf/index.html) 经过 [@LeonieWatson](https://twitter.com/LeonieWatson)
- [Web Components and Styles Scoping](https://www.dropbox.com/s/wdh9uufjui5htll/Web-Components-and-Styles-Scoping-经过-bashmish-FrontMania-2018.pdf) 经过 [@bashmish](https://twitter.com/bashmish)
- [Web Components can do that?!](https://slides.com/vogloblinsky/web-components-can-do-that) 经过 [@vogloblinsky](https://twitter.com/vogloblinsky)
- [Web Components: Introduction and State of the Art](https://webcomponents.dev/blog/web-components-slides/) 经过 [@webcomp_dev](https://twitter.com/webcomp_dev)

### Talks

- [Better Apps: Delivering Universal UI Patterns as Web Components](https://youtu.be/mtHf7crZZIQ) 经过 [@janmiksovsky](https://twitter.com/janmiksovsky)
- [Custom Web Shadow Elements, or Whatever…](https://vimeo.com/364370506) 经过 [@aerotwist](https://twitter.com/aerotwist)
- [Styling and Theming Web Components](https://youtu.be/FM7ROEVPA4k) 经过 [@justinfagnani](https://twitter.com/justinfagnani)
- [Web Components at Enterprise Scale](https://youtu.be/iFp-P2UJT_Y) 经过 [@diervo](https://twitter.com/diervo)

## Usage Metrics

- [Chrome Platform Status: `CustomElementRegistryDefine`](https://chromestatus.com/metrics/feature/timeline/popularity/1689)
- [Chrome Platform Status: `ElementAttachShadow`](https://chromestatus.com/metrics/feature/timeline/popularity/804)
- [Chrome Platform Status: `HTMLTemplateElement`](https://chromestatus.com/metrics/feature/timeline/popularity/2769)

## Proposals

### Form-associated Custom Elements

- [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) - Google Chrome 团队的文档.
- [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) - Chrome 平台状态中的功能.
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements/form-associated)

### Custom State Pseudo class

- [Blink: Intent to implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/CApU9QIu3TM)
- [`ElementInternals`'s `states` property and the `:state()` pseudo class](https://github.com/w3c/webcomponents/blob/gh-pages/proposals/custom-states-and-state-pseudo-class.md)

### Constructable Stylesheet Objects

- [Specification Draft](https://wicg.github.io/construct-stylesheets/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html)
- [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md)
- [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) - Chrome 平台状态中的功能.

## Miscellaneous

- [bruck](https://github.com/Heydon/bruck) - 使用 Web 组件和 Houdini Paint API 构建的原型系统.
- [Vaadin Directory](https://vaadin.com/directory) - 发布、讨论和评价 Web 组件
- [webcomponents.org](http://webcomponents.org/) - 讨论和共享 Web 组件.

## History

下面的文章展示了 Web Components 规范走向标准化的长篇故事.
其中一些参考了较早的所谓“v0”Shadow DOM 和自定义元素规范，以及废弃的 HTML 导入规范.
这些材料仅出于历史原因出现在这里，它们按年份分组并按时间顺序列出.

### 2019

- [A history of the HTML slot element](https://component.kitchen/blog/posts/a-history-of-the-html-slot-element)
- [Web Components in 2019: An Overview of the Most Exciting Proposals for the Web Platform Related to Web Components](https://scotch.io/bar-talk/an-overview-of-the-most-exciting-proposals-for-the-web-platform-related-to-web-components)

### 2018

- [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
- [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)

### 2017

- [Web Components: The Long Game](https://infrequently.org/2017/10/web-components-the-long-game/)
- [An intro to web components with otters](https://meowni.ca/posts/web-components-with-otters/)
- [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/)
- [Regarding the broken promise of Web Components](http://robdodson.me/regarding-the-broken-promise-of-web-components/)

### 2016

- [Introducing Custom Elements](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019)

### 2015

- [Introducing Slot-Based Shadow DOM API](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/)
- [Microsoft Edge and Web Components](https://blogs.windows.com/msedgedev/2015/07/15/microsoft-edge-and-web-components/)
- [Bringing componentization to the web: An overview of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
- [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components/)

### 2014

- [A No-Nonsense Guide to Web Components](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/)
- [Mozilla and Web Components: Update](https://hacks.mozilla.org/2014/12/mozilla-and-web-components/)
- [The State of the Componentised Web](https://www.leggetter.co.uk/2014/08/06/state-componentised-web.html)
- [Building an Accessible Disclosure Button – using Web Components](https://developer.paciellogroup.com/blog/2014/06/accessible-disclosure-button-using-web-components/)
- [Web Components and you – dangers to avoid](https://christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/)
- [The Web's Declarative, Composable Future](https://addyosmani.com/blog/the-webs-declarative-composable-future/)
- [The Shadow DOM Diaries](https://gist.github.com/dglazkov/efd2deec54f65aa86f2e)
- [A Detailed Introduction To Custom Elements](https://www.smashingmagazine.com/2014/03/introduction-to-custom-elements/)

### 2013

- [Performance and Custom Elements](https://www.stevesouders.com/blog/2013/11/26/performance-and-custom-elements/)
- [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/)
- [Creating Reusable Markup with The HTML Template Element](https://blog.teamtreehouse.com/creating-reusable-markup-with-the-html-template-element)
- [Working with Shadow DOM](https://blog.teamtreehouse.com/working-with-shadow-dom)
- [HTML's New Template Tag](https://www.html5rocks.com/en/tutorials/webcomponents/template/)

### 2012

- [The Basics of the Shadow DOM](https://www.sitepoint.com/the-basics-of-the-shadow-dom/)
- [Notes on Web Components + ARIA](https://developer.paciellogroup.com/blog/2012/07/notes-on-web-components-aria/)
- [Introduction to Web Components](https://www.w3.org/TR/2012/WD-components-intro-20120522/)

### 2011

- [Web Components and Model Driven Views by Alex Russell](https://fronteers.nl/congres/2011/sessions/web-components-and-model-driven-views-alex-russell)
- [What the Heck is Shadow DOM?](https://glazkov.com/2011/01/14/what-the-heck-is-shadow-dom/)

## Who To Follow

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://twitter.com/polymer">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1063502058337136640/RmlG_bbW_80x80.jpg">
          <div>聚合物</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/stenciljs">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1135534552137510914/5ZzvOFFp_80x80.png">
          <div>模版</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/openwc">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1101188623930662912/YKlBD7n6_80x80.png">
          <div>open-wc.org</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/webcomp_dev">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1169270943371407360/U-90Bxn0_80x80.jpg">
          <div>webcomponents.dev</div>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://twitter.com/justinfagnani">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/378800000808710206/2dbdaa1cb7b0db02f997aea5b40f29b8_80x80.jpeg">
          <div>贾斯汀法格纳尼</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/viljamis">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/671595827740086273/wCUWq-1S_80x80.png">
          <div>维尔雅米·萨尔米宁</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/JanMiksovsky">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/675000078055051264/u1ZEQfeE_80x80.jpg">
          <div>扬·米克索夫斯基</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/serhiikulykov">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1028197887329685504/cM6nOHlp_80x80.jpg">
          <div>谢尔希·库雷科夫</div>
        </a>
      </td>
    </tr>
  <tbody>
</table>

## License

版权所有 2014-2018，保留所有权利.

获得许可的代码：
[MIT license](http://mateusortiz.mit-license.org)

@作者马特乌斯奥尔蒂斯<mteusortiz@gmail.com>
