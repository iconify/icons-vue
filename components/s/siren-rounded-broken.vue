<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wyhd3xbev"/><path class="zzy6285ft"/><path class="ssofjby4d"/><path class="i7pqdab_g"/><path class="j54-w6byv"/><path class="e-4bmobwc"/><path class="obcs1cbgf"/><path class="y1v0gkt2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siren-rounded-broken" /></template>
<style>
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

.obcs1cbgf {
  d: path("M12 19V22");
}

.ssofjby4d {
  d: path("M12 2V5");
}

.wyhd3xbev {
  d: path("M20 22V16C20 11.5817 16.4183 8 12 8C9.03887 8 6.4535 9.60879 5.07026 12M4 22V16");
}

.y1v0gkt2m {
  d: path("M2 22H14M18 22H22");
}

.zzy6285ft {
  d: path("M14.291 11.5C15.2937 11.9059 16.0944 12.7065 16.5003 13.7092");
}

</style>
