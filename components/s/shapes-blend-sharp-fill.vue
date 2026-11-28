<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t_iv1gn1z"/><path clip-rule="evenodd" class="d-guv_bnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-blend-sharp-fill" /></template>
<style>
.d-guv_bnr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.243 11.757C21.327 12.842 22 14.343 22 16C22 19.314 19.314 22 16 22C12.686 22 10 19.314 10 16C10 12.686 12.686 10 16 10C17.657 10 19.158 10.673 20.243 11.757Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t_iv1gn1z {
  d: path("M3 13V3H13M7 17V10C7 8.343 8.343 7 10 7H17");
}

</style>
