<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aoqo0okvt"/><path class="dmofyebyj"/><path class="eqwwmzbmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trace-outline-bold" /></template>
<style>
.aoqo0okvt {
  d: path("M3 6.5A1.5 1.5 0 0 1 4.5 5h7A1.5 1.5 0 0 1 13 6.5 1.5 1.5 0 0 1 11.5 8h-7A1.5 1.5 0 0 1 3 6.5");
}

.dmofyebyj {
  d: path("M7 12.5A1.5 1.5 0 0 1 8.5 11h8a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-8A1.5 1.5 0 0 1 7 12.5");
}

.eqwwmzbmp {
  d: path("M11 18.5a1.5 1.5 0 0 1 1.5 -1.5h6a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-6a1.5 1.5 0 0 1 -1.5 -1.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
