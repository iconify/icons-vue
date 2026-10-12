<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wb-0y6b5a"/><path class="sx-4gqbte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paratha" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sx-4gqbte {
  d: path("M7.67 9.5a5 5 0 0 1 3.04-2.33");
}

.wb-0y6b5a {
  d: path("M12 3.5q2.52-.92 4.25 1.14q2.64.47 3.11 3.11Q21.42 9.48 20.5 12q.92 2.52-1.14 4.25q-.47 2.64-3.11 3.11q-1.73 2.06-4.25 1.14q-2.52.92-4.25-1.14q-2.64-.47-3.11-3.11Q2.58 14.52 3.5 12q-.92-2.52 1.14-4.25q.47-2.64 3.11-3.11Q9.48 2.58 12 3.5");
}

</style>
