<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1vgu1brh"/><path class="jotdonbiv"/><path class="n2l08-bfj"/><path class="ccgk_xb3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:server-outline-thin" /></template>
<style>
.ccgk_xb3n {
  d: path("M7 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e1vgu1brh {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v4.5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jotdonbiv {
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n2l08-bfj {
  d: path("M4 15.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
