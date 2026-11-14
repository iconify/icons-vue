<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lczvimtfk"/><path class="i6culxb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:onsite-daycare" /></template>
<style>
.i6culxb7y {
  d: path("m14.5 9.5l2-5C17 3.5 18 3 19 3.25l2.25 2.25c.25.5 0 1.25-.75 1.25h-2l-1.25 3M3 18.5c4 2.5 14 2.5 18 0M8 14l-1.25 5.25M14.5 14l1.25 5.25M6 11l-2.5 2.5");
}

.lczvimtfk {
  d: path("M6 9.5h10.5V14H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
