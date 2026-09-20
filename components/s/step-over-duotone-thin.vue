<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hf_gtezns"/><path class="yfusq_w1s"/><path class="a6thxobqf"/><path class="xyj-l9cjp"/><path class="ilnpzmblt"/><path class="b1o8mue8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-over-duotone-thin" /></template>
<style>
.a6thxobqf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b1o8mue8c {
  d: path("m15 11 3 3 3 -3");
}

.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilnpzmblt {
  d: path("M6 14a6 6 0 0 1 12 0");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.yfusq_w1s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
