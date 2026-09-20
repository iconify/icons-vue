<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ut22q-b2l"/><path class="qx4fzbhlz"/><path class="ah0cuqn_g"/><path class="q534om6ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sd-card-outline-thin" /></template>
<style>
.ah0cuqn_g {
  d: path("M11 5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q534om6ef {
  d: path("M14 8v4");
}

.qx4fzbhlz {
  d: path("M8 5v4");
}

.ut22q-b2l {
  d: path("M4 2h11l5 5v15H4Z");
}

</style>
