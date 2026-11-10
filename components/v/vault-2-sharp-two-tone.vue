<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d2mg7hf_r"/><path class="vf0m_8ldh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vault-2-sharp-two-tone" /></template>
<style>
.d2mg7hf_r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 2C21.552 2 22 2.45 22 3V21C22 21.55 21.552 22 21 22H3C2.448 22 2 21.55 2 21V3C2 2.45 2.448 2 3 2H21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vf0m_8ldh {
  d: path("M14.121 9.88L17.293 6.71M6.707 17.29L9.879 14.12M17.293 17.29L14.121 14.12M9.879 9.88L6.707 6.71M3 3H21V21H3V3ZM12 15C10.343 15 9 13.66 9 12C9 10.34 10.343 9 12 9C13.657 9 15 10.34 15 12C15 13.66 13.657 15 12 15Z");
}

</style>
