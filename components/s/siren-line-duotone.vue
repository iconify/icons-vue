<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w9n449bmp"/><path class="b4ae6zb-r"/><path class="yw2wdncae"/><path class="ssofjby4d"/><path class="mbihc-bcr"/><path class="w463bhbii"/><path class="e-4bmobwc"/><path class="xlhb24b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siren-line-duotone" /></template>
<style>
.b4ae6zb-r {
  d: path("M15 10.8149C16.23 10.8149 17.23 11.77 17.1851 13");
}

.e-4bmobwc {
  d: path("M13.5 17.5C13.5 18.3284 12.8284 19 12 19C11.1716 19 10.5 18.3284 10.5 17.5C10.5 16.6716 11.1716 16 12 16C12.8284 16 13.5 16.6716 13.5 17.5Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbihc-bcr {
  d: path("M21 5L19.5 6.5");
}

.ssofjby4d {
  d: path("M12 2V5");
}

.w463bhbii {
  d: path("M3 5L4.5 6.5");
}

.w9n449bmp {
  d: path("M20 22V16C20 13.1997 20 11.7996 19.455 10.73C18.9757 9.78924 18.2108 9.02433 17.27 8.54497C16.2004 8 14.8003 8 12 8C9.19974 8 7.79961 8 6.73005 8.54497C5.78924 9.02433 5.02433 9.78924 4.54497 10.73C4 11.7996 4 13.1997 4 16V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xlhb24b0z {
  d: path("M12 19V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yw2wdncae {
  d: path("M2 22H22");
}

</style>
