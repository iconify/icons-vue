<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2x-_sd5q"/><path class="zesf2kblt"/><path class="uxyzhxvwz"/><path class="f4wf9tbjy"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tree-of-thought-outline-thin" /></template>
<style>
.f4wf9tbjy {
  d: path("m7 14 5 5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2x-_sd5q {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.t7ql4f28h {
  d: path("m19 10 2 2 -2 2");
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

.zesf2kblt {
  d: path("m7 10 5 -5h5");
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
