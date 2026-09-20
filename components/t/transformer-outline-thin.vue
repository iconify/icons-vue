<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iaozfqbuj"/><path class="duvzkqbwy"/><path class="m6r9k7-tj"/><path class="w_jkatblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transformer-outline-thin" /></template>
<style>
.duvzkqbwy {
  d: path("M8 9.5h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.m6r9k7-tj {
  d: path("M8 14.5h8");
}

.w_jkatblo {
  d: path("M12 7v10");
}

</style>
