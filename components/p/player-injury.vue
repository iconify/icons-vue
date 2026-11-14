<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="raifh55ml"/><path class="lp35ljv5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:player-injury" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lp35ljv5v {
  d: path("M4.5 6.75h10l3-2.25m-3 2.25l3 2.25m.5 5.75v3.5M18 21h.01");
}

.raifh55ml {
  d: path("M4.5 7.75a5 5 0 1 0 10 0a5 5 0 1 0-10 0M3.25 21.5c0-4.5 3-6 6.25-6c2.498 0 4.848.886 5.802 3.34m.174.52q.039.135.072.276");
}

</style>
