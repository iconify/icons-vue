<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gnpa19brn"/><path class="qlbhb_rqn"/><path clip-rule="evenodd" class="o8k-u4bfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-sharp-duotone" /></template>
<style>
.gnpa19brn {
  stroke-opacity: 0.4;
  d: path("M3 9V3H9M15 3H21V9M21 15V21H15M9 21H3V15");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8k-u4bfu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 10.034V9.424C6 9.041 6.219 8.691 6.564 8.524L11.564 6.1C11.7 6.034 11.849 6 12 6C12.151 6 12.3 6.034 12.436 6.1L14.936 7.312L17.436 8.524C17.781 8.691 18 9.041 18 9.424V10.034L12.458 12.889C12.316 12.962 12.159 13 12 13C11.841 13 11.684 12.962 11.542 12.889L6 10.034Z");
  stroke: none;
}

.qlbhb_rqn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.936 7.312L17.436 8.524C17.781 8.691 18 9.041 18 9.424V14.576C18 14.959 17.781 15.309 17.436 15.476L12.436 17.9C12.3 17.966 12.151 18 12 18C11.849 18 11.7 17.966 11.564 17.9L6.564 15.476C6.219 15.309 6 14.959 6 14.576V9.424C6 9.041 6.219 8.691 6.564 8.524L11.564 6.1C11.7 6.034 11.849 6 12 6C12.151 6 12.3 6.034 12.436 6.1L14.936 7.312Z");
  stroke: none;
}

</style>
