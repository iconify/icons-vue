<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dq6-dccyq"/><path class="zzy6285ft"/><path class="yw2wdncae"/><path class="ssofjby4d"/><path class="i7pqdab_g"/><path class="j54-w6byv"/><path class="e-4bmobwc"/><path class="xlhb24b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siren-rounded-line-duotone" /></template>
<style>
.dq6-dccyq {
  d: path("M20 22V16C20 11.5817 16.4183 8 12 8C7.58172 8 4 11.5817 4 16V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.e-4bmobwc {
  d: path("M13.5 17.5C13.5 18.3284 12.8284 19 12 19C11.1716 19 10.5 18.3284 10.5 17.5C10.5 16.6716 11.1716 16 12 16C12.8284 16 13.5 16.6716 13.5 17.5Z");
}

.i7pqdab_g {
  d: path("M21 6L19.5 7.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j54-w6byv {
  d: path("M3 6L4.5 7.5");
}

.ssofjby4d {
  d: path("M12 2V5");
}

.xlhb24b0z {
  d: path("M12 19V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yw2wdncae {
  d: path("M2 22H22");
}

.zzy6285ft {
  d: path("M14.291 11.5C15.2937 11.9059 16.0944 12.7065 16.5003 13.7092");
}

</style>
