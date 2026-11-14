<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o3ddcob1l"/><path class="b6apq_b2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:query-slow" /></template>
<style>
.b6apq_b2i {
  d: path("M7 10.5L4.5 13L7 15.5m3.5-5.5l-1.75 6m3.5-5.5l2.333 2.333M17.5 20a2.5 2.5 0 1 1 2-2.5a1.25 1.25 0 1 1-2.25 0M14 21.25h7.5m-.75 0l.5-2.5l-.5-1.75m.5 1.75l.75-1.5");
}

.o3ddcob1l {
  d: path("M11.2 20.5H2.5v-17h19v10.4m-19-6.15h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
