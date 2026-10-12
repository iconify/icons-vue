<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-vvuiehl"/><path class="bfbj0lbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sso-login" /></template>
<style>
.bfbj0lbyp {
  d: path("M10.75 8.25L14.5 12l-3.75 3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u-vvuiehl {
  d: path("M13 2.75h5.5a2.75 2.75 0 0 1 2.75 2.75v13a2.75 2.75 0 0 1-2.75 2.75H13M3 12h11.5");
}

</style>
