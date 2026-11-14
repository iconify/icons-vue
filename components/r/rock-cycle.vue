<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gaqkn6bgq"/><path class="xddcc2bdh"/><path class="q7gqw2bbs"/><path class="v6x9tspcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rock-cycle" /></template>
<style>
.gaqkn6bgq {
  d: path("m8 13.375l.203-1.115a1.5 1.5 0 0 1 .18-.488l1.214-2.081a1.5 1.5 0 0 1 1.202-.741l2.356-.147a1.5 1.5 0 0 1 1.327.643l1.501 2.169a1.5 1.5 0 0 1 .267.854v.906a1.375 1.375 0 0 1-1.375 1.375H9.148A1.166 1.166 0 0 1 8 13.375M8.25 12h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7gqw2bbs {
  d: path("M13.75 18.25L12 20l1.75 1.75M8 18.928A8 8 0 0 1 12 4");
}

.v6x9tspcc {
  d: path("M10.25 2.25L12 4l-1.75 1.75");
}

.xddcc2bdh {
  d: path("M16 5.072A8 8 0 0 1 12 20");
}

</style>
