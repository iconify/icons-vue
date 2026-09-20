<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="r-0uhlbzq"><circle class="fuu_ksbfy"/><path class="advo2wbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:peace-symbol" /></template>
<style>
.advo2wbmd {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M64 6v116m0-58l41.01 41.01m-82.02 0L64 64");
}

.fuu_ksbfy {
  cx: 64px;
  cy: 64px;
  r: 58px;
}

.r-0uhlbzq {
  fill: none;
  stroke: var(--svg-color--f79229, #f79229);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--11px, 11px);
}

</style>
