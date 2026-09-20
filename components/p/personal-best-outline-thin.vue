<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o8p9igehf"/><path class="lkivjibuo"/><path class="qdn88l2uv"/><path class="bdehoybwy"/><path class="bx6cs-b9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:personal-best-outline-thin" /></template>
<style>
.bdehoybwy {
  d: path("M8 8.5a2.5 2.5 0 0 1 0 -5");
}

.bx6cs-b9q {
  d: path("M16 3.5a2.5 2.5 0 0 1 0 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkivjibuo {
  d: path("M12 13v7");
}

.o8p9igehf {
  d: path("M8 3h8v6l-4 4 -4 -4Z");
}

.qdn88l2uv {
  d: path("M7 20h10");
}

</style>
