<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owy2rxb_w"/><path class="v0xwkvbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:token-expire" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.owy2rxb_w {
  d: path("M19 12a7 7 0 1 1-7-7");
}

.v0xwkvbcv {
  d: path("M12 8.5V12h3m1.42-4.42l1.06-1.06");
}

</style>
