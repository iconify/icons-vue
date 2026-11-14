<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uabmqfx1j"/><path class="eigv7acpm"/><path class="ipzmthfyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pollination" /></template>
<style>
.eigv7acpm {
  d: path("M13.5 8.5a2.5 3.5 0 1 0 5 0a2.5 3.5 0 1 0-5 0Z");
}

.ipzmthfyt {
  d: path("M10.75 6a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm6.75 0a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm-2-3l-.75-.75m2 .75l.75-.75M13.75 8h4.75M14 9.75h4.25M7.5 16h.01");
}

.uabmqfx1j {
  d: path("m7.5 11l1.616 2.775l3.139.68l-2.14 2.395l.324 3.195L7.5 18.75l-2.939 1.295l.324-3.195l-2.14-2.395l3.139-.68ZM15 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
