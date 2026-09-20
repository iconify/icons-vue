<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="ly7sc7y4x"/><path class="fd7q-d8sx"/><path class="flhmwp83q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:otel-collector-outline-thin" /></template>
<style>
.fd7q-d8sx {
  d: path("M6.5 6.5 11 11");
}

.flhmwp83q {
  d: path("M17.5 6.5 13 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ly7sc7y4x {
  d: path("M12 5v7");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

</style>
