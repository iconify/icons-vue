<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b6rlx8mlt"/><path class="ljad-6hjd"/><path class="ghavz0bas"/><path class="t847zkbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:virus-cell-outline-thin" /></template>
<style>
.b6rlx8mlt {
  d: path("M12 5q4.5 0 6 3c2 1 2 5 0 7q-1.5 3 -6 3t-6 -3c-2 -2 -2 -6 0 -7q1.5 -3 6 -3");
}

.ghavz0bas {
  d: path("m19 8 3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ljad-6hjd {
  d: path("M12 5V2");
}

.t847zkbua {
  d: path("m5 16 -3 3");
}

</style>
