<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ybcxlk3cu"/><path class="tcfruqbqd"/><circle class="g5vbm32li"/><circle class="xr65xs9xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowplow-sharp" /></template>
<style>
.g5vbm32li {
  cx: 10.75px;
  cy: 18.75px;
  r: 2px;
}

.tcfruqbqd {
  d: path("M14 7v4.25H9.75m-5 3H7.5m-4.75-4.5H4l.525.005l.175.495c.6 2.25.6 4.25 0 6.5l-.175.495L4 17.25H2.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xr65xs9xo {
  cx: 18px;
  cy: 18.75px;
  r: 2px;
}

.ybcxlk3cu {
  d: path("M7.5 15.75v-4.5h2.25l1.85-3.5l.443-.768l.887.018h4.32v4.25h3.5v5.5H7.5z");
}

</style>
