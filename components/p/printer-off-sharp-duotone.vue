<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f2trvzwqq"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:printer-off-sharp-duotone" /></template>
<style>
.f2trvzwqq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.88 16L15 16H7V21H17V20V17.12L19.88 20H19V22C19 22.552 18.552 23 18 23H6C5.448 23 5 22.552 5 22V20H2C1.448 20 1 19.552 1 19V10C1 9.452 1.441 9.006 1.988 9H8.88L15.88 16ZM6.657 3V1H7.657H14C14.265 1 14.52 1.105 14.707 1.293L18.707 5.293C18.895 5.48 19 5.735 19 6V9H22C22.552 9 23 9.448 23 10V19C23 19.104 22.984 19.204 22.955 19.298L12.657 9H17V6.414L13.586 3H7.657L6.657 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

</style>
