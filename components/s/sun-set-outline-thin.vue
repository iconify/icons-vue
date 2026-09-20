<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eu2so4bxo"/><path class="z9ittvbis"/><path class="fd_pyz_no"/><path class="uh7f2-ziy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sun-set-outline-thin" /></template>
<style>
.eu2so4bxo {
  d: path("M7 16a5 5 0 0 1 10 0");
}

.fd_pyz_no {
  d: path("M12 5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uh7f2-ziy {
  d: path("M9.5 6.5 12 9l2.5 -2.5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
