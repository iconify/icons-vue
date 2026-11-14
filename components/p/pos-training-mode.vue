<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jcxkuqbyd"/><path class="gybvl8b6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-training-mode" /></template>
<style>
.gybvl8b6f {
  d: path("M16 16.5V19c1.25 1.25 2.75 1.25 4 0v-2.5m1-.75v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcxkuqbyd {
  d: path("M6 2.5h7.5A3.5 3.5 0 0 1 17 6v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 9V6A3.5 3.5 0 0 1 6 2.5m2.75 10V19m-3 0h6A1.25 1.25 0 0 1 13 20.25a1.25 1.25 0 0 1-1.25 1.25h-6a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.75 19M5.5 6h5m-5 3.25H8m3 0h3m.75 6L18 14l3.25 1.25q.5.25 0 .5L18 17l-3.25-1.25q-.5-.25 0-.5");
}

</style>
