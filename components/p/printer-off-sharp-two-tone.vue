<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bewo-z6lk"/><path class="io5iybbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:printer-off-sharp-two-tone" /></template>
<style>
.bewo-z6lk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 20H19V22C19 22.552 18.552 23 18 23H6C5.448 23 5 22.552 5 22V20H2C1.448 20 1 19.552 1 19V10C1 9.452 1.441 9.007 1.988 9H9L20 20ZM5.142 1.485C5.317 1.195 5.636 1 6 1H14C14.265 1 14.52 1.105 14.707 1.293L18.707 5.293C18.895 5.48 19 5.735 19 6V9H22C22.552 9 23 9.448 23 10V19C23 19.104 22.984 19.204 22.955 19.298L5.142 1.485Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.io5iybbsj {
  d: path("M6 19H2V10H10M18 18V22H6V15H15M1.707 1.707L22.293 22.293");
}

</style>
