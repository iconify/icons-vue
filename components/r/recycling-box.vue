<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tvf4qlbdt"/><path class="udnk23m5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycling-box" /></template>
<style>
.tvf4qlbdt {
  d: path("M2.5 6.5h19M4 6.5v13a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-13m-11 0v-3h6v3");
}

.udnk23m5h {
  d: path("m7.75 16.5l2.75-4.75l-2.25.5m5.25-.5L16 16l.5-2.5M15 18.75H9.5L11.25 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
