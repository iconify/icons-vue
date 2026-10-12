<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3ey8eb2r"/><path class="rci7ivfru"/><path class="r6264y6ri"/><path class="uy4u_it9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tomato-vine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3ey8eb2r {
  d: path("M12.25 21.25c-1-2.25-1-4.25 0-6.5s1-4.25 0-6.5s-1-3.25 0-5.5");
}

.r6264y6ri {
  d: path("M2.75 10a3 3 0 1 0 6 0a3 3 0 1 0-6 0m12.5 5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.rci7ivfru {
  d: path("M11.6 7.25C9.5 6 7.25 6 5.75 7m6.15 4.75c2.25-.75 4.5-.75 6.35.25");
}

.uy4u_it9z {
  d: path("m5.25 10l.5-1.75l.5 1.75m11.5 5l.5-1.75l.5 1.75");
}

</style>
