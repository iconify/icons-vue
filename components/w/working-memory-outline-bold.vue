<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c68dutvfq"/><path class="w28ybhbjm"/><path class="h7bcztycq"/><path class="h0r-78wsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:working-memory-outline-bold" /></template>
<style>
.c68dutvfq {
  d: path("M15 5h4a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h4");
}

.h0r-78wsa {
  d: path("M17 10v4");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w28ybhbjm {
  d: path("M7 10v4");
}

</style>
