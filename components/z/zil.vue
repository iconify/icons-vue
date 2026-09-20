<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGijhFLcKr)" class="o8mbgz0so"/><path fill="url(#SVG53izbbcH)" class="ci8i_yl6p"/><path fill="url(#SVGzUrxeMZn)" class="tzag0rf_y"/><defs><linearGradient id="SVGijhFLcKr" x1="16.24" x2="3.146" y1="20.445" y2="15.548" gradientUnits="userSpaceOnUse"><stop class="uk2uxngyq"/><stop offset="1" class="lpyrqobec"/></linearGradient><linearGradient id="SVG53izbbcH" x1="12" x2="12" y1="2.999" y2="21" gradientUnits="userSpaceOnUse"><stop class="blqhdbb7r"/><stop offset="1" class="rc2xl5-1i"/></linearGradient><linearGradient id="SVGzUrxeMZn" x1="14.117" x2="19.941" y1="18.619" y2="13.854" gradientUnits="userSpaceOnUse"><stop class="blqhdbb7r"/><stop offset="1" class="rc2xl5-1i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zil" /></template>
<style>
.blqhdbb7r {
  stop-color: var(--svg-color--5ac1c1, #5ac1c1);
}

.ci8i_yl6p {
  d: path("M5.647 4.153v2.621l6.999 3.372l-7 3.426v2.584L15.707 21v-2.594l-6.814-3.31l6.814-3.494V9.008L5.646 4.164z");
}

.ft5dv1b6b {
  fill: none;
}

.lpyrqobec {
  stop-color: var(--svg-color--347181, #347181);
}

.o8mbgz0so {
  d: path("M5.647 4.154L15.7 9.01l2.647-1.165L8.278 3z");
}

.rc2xl5-1i {
  stop-color: var(--svg-color--216b79, #216b79);
}

.tzag0rf_y {
  d: path("m15.706 8.994l2.647-1.15v2.595l-2.647 1.154zm0 11.986l2.647-1.154v-8.074l-2.647 1.165z");
}

.uk2uxngyq {
  stop-color: var(--svg-color--60aaac, #60aaac);
}

</style>
