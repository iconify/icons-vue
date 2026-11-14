<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vspug48qm"/><path class="pg0qle-4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:training-schedule" /></template>
<style>
.pg0qle-4k {
  d: path("M10 12.75h6v2.5h-3.5a2.5 2.5 0 1 1-2.5-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vspug48qm {
  d: path("M3 4.5h18V21H3Zm5-2v3.75m8-3.75v3.75M3 9h18");
}

</style>
