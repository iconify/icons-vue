<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oypzkhe7l"/><path class="q0e54nb2g"/><path class="b5vhyhbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-net-goal" /></template>
<style>
.b5vhyhbcy {
  d: path("m12 12l2 1.5l-.75 2h-2.5l-.75-2Zm0 0V9.5m2 4l2.25-1m-3 3l1.5 2.25m-4-2.25l-1.5 2.25M10 13.5l-2.25-1");
}

.oypzkhe7l {
  d: path("M3 20V5h18v15");
}

.q0e54nb2g {
  d: path("M7.5 14a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
