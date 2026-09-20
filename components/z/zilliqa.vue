<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGpFnYgcAZ)" class="j_lpqgb4p"/><path fill="url(#SVG53izbbcH)" class="azo1isbwx"/><path fill="url(#SVGMX7kWduc)" class="h16rjgsbh"/><defs><linearGradient id="SVGpFnYgcAZ" x1="16.24" x2="3.147" y1="20.445" y2="15.548" gradientUnits="userSpaceOnUse"><stop class="uk2uxngyq"/><stop offset="1" class="lpyrqobec"/></linearGradient><linearGradient id="SVG53izbbcH" x1="12" x2="12" y1="2.999" y2="21" gradientUnits="userSpaceOnUse"><stop class="blqhdbb7r"/><stop offset="1" class="rc2xl5-1i"/></linearGradient><linearGradient id="SVGMX7kWduc" x1="14.117" x2="19.942" y1="18.618" y2="13.853" gradientUnits="userSpaceOnUse"><stop class="blqhdbb7r"/><stop offset="1" class="rc2xl5-1i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zilliqa" /></template>
<style>
.azo1isbwx {
  d: path("M5.647 4.154v2.62l7 3.373l-7 3.425v2.583L15.707 21v-2.594l-6.814-3.31l6.813-3.492V9.01L5.647 4.164z");
}

.blqhdbb7r {
  stop-color: var(--svg-color--5ac1c1, #5ac1c1);
}

.ft5dv1b6b {
  fill: none;
}

.h16rjgsbh {
  d: path("m15.706 8.994l2.647-1.15v2.595l-2.647 1.154zm0 11.986l2.647-1.155v-8.072l-2.647 1.164z");
}

.j_lpqgb4p {
  d: path("M5.647 4.155L15.701 9.01l2.648-1.165L8.279 3z");
}

.lpyrqobec {
  stop-color: var(--svg-color--347181, #347181);
}

.rc2xl5-1i {
  stop-color: var(--svg-color--216b79, #216b79);
}

.uk2uxngyq {
  stop-color: var(--svg-color--60aaac, #60aaac);
}

</style>
