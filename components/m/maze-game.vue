<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfqqbwbhu"/><path class="c3nhkv2au"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:maze-game" /></template>
<style>
.c3nhkv2au {
  d: path("M12 21v-9h4.5m-9 0v4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rfqqbwbhu {
  d: path("M8 3h11a2 2 0 0 1 2 2v11M3 8v11a2 2 0 0 0 2 2h16M7.5 7.5h9");
}

</style>
