<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6h0tjbiq"/><path class="wiboc7buh"/><path class="f50fjsbgi"/><path class="o8od38cnm"/><path class="sjev68umd"/><path class="evsu0jbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:uv-low-outline-thin" /></template>
<style>
.e6h0tjbiq {
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.evsu0jbbm {
  d: path("M10 14v4");
}

.f50fjsbgi {
  d: path("M19.5 3.5 17 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.sjev68umd {
  d: path("M6 11v7");
}

.wiboc7buh {
  d: path("M4.5 3.5 7 6");
}

</style>
