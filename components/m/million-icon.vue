<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":182};
const content = `<defs><radialGradient id="SVGoY1tRcNF" cx="50%" cy="49.999%" r="32.306%" fx="50%" fy="49.999%" gradientTransform="matrix(0 447.7271 0 -15.63497 0 -380193.475)"><stop offset="0%" class="wna4jfbrn"/><stop offset="100%" class="u7f41fynk"/></radialGradient><radialGradient id="SVGhDcUNdYY" cx="50.061%" cy="104.167%" r="67.301%" fx="50.061%" fy="104.167%" gradientTransform="matrix(0 4432.29832 0 -154.77927 0 -35820434.112)"><stop offset="0%" class="wna4jfbrn"/><stop offset="100%" class="u7f41fynk"/></radialGradient><radialGradient id="SVGv5oTJbDq" cx="99.122%" cy="34.222%" r="42.521%" fx="99.122%" fy="34.222%" gradientTransform="matrix(0 6883.80402 0 -240.38773 0 -56809933.375)"><stop offset="0%" class="wna4jfbrn"/><stop offset="100%" class="u7f41fynk"/></radialGradient><radialGradient id="SVGeX0xFczF" cx=".878%" cy="34.21%" r="42.506%" fx=".878%" fy="34.21%" gradientTransform="matrix(0 688.58028 0 -24.04575 0 -5447320.88)"><stop offset="0%" class="wna4jfbrn"/><stop offset="100%" class="u7f41fynk"/></radialGradient></defs><path fill="url(#SVGoY1tRcNF)" class="eth-imb_w"/><path fill="url(#SVGhDcUNdYY)" class="ou_roq7az"/><path fill="url(#SVGv5oTJbDq)" class="vlnqtnb3l"/><path fill="url(#SVGeX0xFczF)" class="h9xlw0b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:million-icon" /></template>
<style>
.eth-imb_w {
  d: path("M64.995 153.355c11.777-16.858 35.745-28.399 63.396-28.399c27.65 0 51.62 11.54 63.397 28.4c-11.778 16.856-35.746 28.397-63.397 28.397s-51.619-11.54-63.396-28.398");
}

.h9xlw0b-g {
  d: path("M256 91.24c-17.124 16.54-40.35 25.831-64.567 25.831s-47.443-9.292-64.567-25.831l64.567-63.143z");
}

.ou_roq7az {
  d: path("M64.567 28.097C76.337 11.418 100.289 0 127.923 0c27.633 0 51.586 11.418 63.356 28.097c-11.77 16.679-35.723 28.097-63.356 28.097S76.337 44.776 64.567 28.097");
}

.u7f41fynk {
  stop-color: var(--svg-color--af73d8, #af73d8);
}

.vlnqtnb3l {
  d: path("M129.133 91.209c-17.124 16.54-40.349 25.831-64.566 25.831S17.124 107.748 0 91.21l64.567-63.112z");
}

.wna4jfbrn {
  stop-color: var(--svg-color--845ce7, #845ce7);
}

</style>
