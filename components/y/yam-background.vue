<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="baxatnwkd"/><path class="tpm3z8d_y"/><path class="b28j2_01b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:yam-background" /></template>
<style>
.b28j2_01b {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.164 7.314c.214-.296.571.165.725.429c1.325 1.698 2.528 5.424 2.479 5.424c-.368-1.187-3.463-5.484-3.204-5.853m-6.738.801c2.696-1.642 4.65-3.368 4.365-3.855s-2.702.448-5.398 2.09s-4.65 3.368-4.365 3.855s2.701-.449 5.398-2.09M4.15 10.87c-.132-.12-.05-.308.01-.385c.418.198 1.858-.176 2.529-.384c-.792.302-2.407.89-2.54.769");
}

.baxatnwkd {
  fill: var(--svg-color--e6de95, #e6de95);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tpm3z8d_y {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.458 11.69a3.6 3.6 0 0 1-.418-1.704c2.863-1.896 8.722-5.71 9.244-5.781a1.7 1.7 0 0 1 1.066.165c4.463 5.122 5.397 9.403 5.622 12.183c.104.732-.027 2.347-1.363 3.001c-1.67.825-3.1-.198-4.259-.473c-1.154-.28-3.517-1.181-4.61-1.884c-1.089-.71-1.523-1.248-2.117-1.803c-.599-.56-2.715-2.918-3.165-3.704");
}

</style>
