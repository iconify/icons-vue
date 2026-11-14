<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocesxbw7q"/><path class="ztvaweboh"/><path class="te7p_bc5x"/><path class="ghoiyebfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payback-period" /></template>
<style>
.ghoiyebfg {
  d: path("m17.25 18.75l2.5-.25L20 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocesxbw7q {
  d: path("M6 4.25a6 1.75 0 1 0 12 0a6 1.75 0 1 0-12 0");
}

.te7p_bc5x {
  d: path("M6 12v1.5a6 1.75 0 0 0 12 0V12M3 15.5a9 6 0 0 0 16.75 3");
}

.ztvaweboh {
  d: path("M6 4.25v1.5a6 1.75 0 0 0 12 0v-1.5M6 12a6 1.75 0 1 0 12 0a6 1.75 0 1 0-12 0");
}

</style>
