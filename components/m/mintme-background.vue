<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="giw_5l6pf"/><path clip-rule="evenodd" class="ww_zap5xl"/><path class="p7nmqobjo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mintme-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.giw_5l6pf {
  fill: var(--svg-color--d1b000, #d1b000);
  d: path("M4 8.108h1.297v1.298H4zm4.324-1.742h1.298V7.62H8.324zM5.297 10.27h1.298v1.297H5.297zm1.73-2.163h1.297v1.298H7.027zM4 14.163h1.297v1.297H4zm3.027 2.162h1.297v1.297H7.027zm-.865-3.46H7.46v1.298H6.162zm7.784-6.919c-.778 0-1.436.147-2.162.45v1.22h-1.298v-.563c-.376.268-.752.64-1.063.982h.199v.938H8.584a7.2 7.2 0 0 0-.571 1.73h.744V12h-.865c0 .411.043.891.121 1.298h1.176v.856l-.865.009c.186.423.597.93.874 1.297v-1.297h1.288v1.297H9.199c.186.246.64.865.856.865h1.297v1.141c.83.394 1.704.584 2.565.588C17.323 18.072 20.004 15.2 20 12c-.004-3.208-2.694-6.054-6.054-6.054m-5.19 4.748V9.393h1.298v1.301z");
}

.p7nmqobjo {
  fill: var(--svg-color--181b1e, #181b1e);
  d: path("m14.33 11.395l-.458 2.335h1.042l.761-3.892h-1.232l-1.713 2.694l-.687-2.694h-1.228l-.761 3.883h1.038l.458-2.34l.515 2.34h.847z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ww_zap5xl {
  fill: var(--svg-color--181b1e, #181b1e);
  fill-rule: evenodd;
  d: path("M19.1 12.168c-.022.086-.043.173-.078.26h-2.326q-.04.277.116.419c.104.1.251.151.411.147c.242.004.472-.104.588-.281h1.094c-.095.19-.238.367-.41.519a2.15 2.15 0 0 1-2.232.311a1.1 1.1 0 0 1-.497-.532a1.3 1.3 0 0 1-.052-.796a1.84 1.84 0 0 1 1.081-1.327c.285-.126.605-.186.921-.186a1.8 1.8 0 0 1 .826.177c.23.121.402.299.489.51c.108.247.13.52.069.779m-1.825-.618a.87.87 0 0 1 .463-.13a.6.6 0 0 1 .42.134c.107.1.146.316.107.445h-1.288c.056-.143.155-.354.302-.45z");
}

</style>
