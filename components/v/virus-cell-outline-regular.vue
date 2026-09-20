<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b6rlx8mlt"/><path class="ljad-6hjd"/><path class="ghavz0bas"/><path class="t847zkbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:virus-cell-outline-regular" /></template>
<style>
.b6rlx8mlt {
  d: path("M12 5q4.5 0 6 3c2 1 2 5 0 7q-1.5 3 -6 3t-6 -3c-2 -2 -2 -6 0 -7q1.5 -3 6 -3");
}

.ghavz0bas {
  d: path("m19 8 3 -3");
}

.ljad-6hjd {
  d: path("M12 5V2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t847zkbua {
  d: path("m5 16 -3 3");
}

</style>
