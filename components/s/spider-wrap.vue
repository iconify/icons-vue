<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eesj7kc9z"/><path class="mffdnhbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spider-wrap" /></template>
<style>
.eesj7kc9z {
  d: path("M5.125 4.5h13.75A2.625 2.625 0 0 1 21.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 16.875v-9.75A2.625 2.625 0 0 1 5.125 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mffdnhbyd {
  d: path("M11.438 9.25h1.125a2.19 2.19 0 0 1 2.187 2.188v1.125a2.19 2.19 0 0 1-2.187 2.187h-1.125a2.19 2.19 0 0 1-2.188-2.187v-1.125a2.19 2.19 0 0 1 2.188-2.188M12 12h.01M12 4.5v4.75m0 5.5v4.75M2.5 12h6.75m5.5 0h6.75");
}

</style>
