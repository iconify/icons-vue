<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_1pk7qez"/><path class="nebfuhbln"/><path class="b8yphbcwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wedding-outline-thin" /></template>
<style>
.b8yphbcwk {
  d: path("m10 7 2 -2 2 2 -2 2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nebfuhbln {
  d: path("M12 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.x_1pk7qez {
  d: path("M4 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
