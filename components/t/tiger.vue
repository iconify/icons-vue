<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="o13bx1btm"/><path class="e--ewzbst"/><path class="lr6id3byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tiger" /></template>
<style>
.e--ewzbst {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 14.25h2l-1 1Zm1 1c0 .75-.5 1.25-1.25 1.25M12 15.25c0 .75.5 1.25 1.25 1.25");
}

.lr6id3byi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 11.25h.01m5.49 0h.01");
}

.o13bx1btm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 9l-.25-3.75c0-.75.75-1.25 1.4-.85L9.5 6c.8-.25 1.65-.4 2.5-.4s1.7.15 2.5.4l2.85-1.6c.65-.4 1.4.1 1.4.85L18.5 9c1 1.25 1.5 2.75 1.5 4.25v1.25l1 1.25l-1.75.25c-1.25 3.25-4 5-7.25 5s-6-1.75-7.25-5L3 15.75l1-1.25v-1.25c0-1.5.5-3 1.5-4.25M12 6.5V9m-8 3.5h2.75m13.25 0h-2.75m-13 2.5H7m12.75 0H17");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
