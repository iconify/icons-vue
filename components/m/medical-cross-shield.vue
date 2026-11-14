<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_zvs3q8k"/><path class="i-0gkz9dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-cross-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-0gkz9dz {
  d: path("M12 7za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 0 15 10a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 13a1.5 1.5 0 0 0-1.5 1.5A1.5 1.5 0 0 1 12 16a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 0 9 13a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 10a1.5 1.5 0 0 0 1.5-1.5A1.5 1.5 0 0 1 12 7");
}

.x_zvs3q8k {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.75-7.5 10.5C8 19.75 4.5 16 4.5 11V5.5Z");
}

</style>
