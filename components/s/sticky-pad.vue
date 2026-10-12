<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1ykqf2vl"/><path class="ics2r351y"/><path class="nmudau01y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticky-pad" /></template>
<style>
.a1ykqf2vl {
  d: path("M16.25 7.75h3a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2h-9.5a2 2 0 0 1-2-2v-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ics2r351y {
  d: path("M4.75 2.75h9.5a2 2 0 0 1 2 2v7l-4.5 4.5h-7a2 2 0 0 1-2-2v-9.5a2 2 0 0 1 2-2");
}

.nmudau01y {
  d: path("M11.75 16.25v-2.5a2 2 0 0 1 2-2h2.5ZM6.25 7h6.5m-6.5 3.25h4");
}

</style>
