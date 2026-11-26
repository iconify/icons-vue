<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="c26svrbyh"/><path class="h-tc6cbxa"/><path clip-rule="evenodd" class="j339ybc_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spline-sharp-fill" /></template>
<style>
.c26svrbyh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 13L6 13C6.5523 13 7 13.4477 7 14L7 18C7 18.5523 6.5523 19 6 19L2 19C1.4477 19 1 18.5523 1 18L1 14C1 13.4477 1.4477 13 2 13ZM20 5L22 5C22.5523 5 23 5.4477 23 6L23 10C23 10.5523 22.5523 11 22 11L18 11C17.4477 11 17 10.5523 17 10L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h-tc6cbxa {
  d: path("M6 16C15 16 9 8 18 8");
}

.j339ybc_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 17C17.5 17.8285 16.8285 18.5 16 18.5C15.1715 18.5 14.5 17.8285 14.5 17C14.5 16.1715 15.1715 15.5 16 15.5C16.8285 15.5 17.5 16.1715 17.5 17ZM9.5 7C9.5 7.8285 8.8285 8.5 8 8.5C7.1715 8.5 6.5 7.8285 6.5 7C6.5 6.1715 7.1715 5.5 8 5.5C8.8285 5.5 9.5 6.1715 9.5 7Z");
  stroke: none;
}

</style>
