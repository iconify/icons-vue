<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ils7yp4cg"/><path class="uk0rveqaj"/><path class="rdx5t34om"/><path class="r09np9bwl"/><path class="rj62dp6ok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:message-bus-outline-bold" /></template>
<style>
.ils7yp4cg {
  d: path("M2 16h20");
}

.r09np9bwl {
  d: path("M6 9.5V16");
}

.rdx5t34om {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rj62dp6ok {
  d: path("M18 9.5V16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uk0rveqaj {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
