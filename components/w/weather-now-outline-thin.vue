<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eyx95fmam"/><path class="kc5-9ib3u"/><path class="o9ikj8but"/><path class="m94qtbc1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weather-now-outline-thin" /></template>
<style>
.eyx95fmam {
  d: path("M4 16a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 7a5.5 5.5 0 0 1 4.5 9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc5-9ib3u {
  d: path("M9 18.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.m94qtbc1o {
  d: path("M12 18.5h2.5");
}

.o9ikj8but {
  d: path("M12 15.5v3");
}

</style>
