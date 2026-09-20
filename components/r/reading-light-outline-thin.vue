<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y--9wccrh"/><path class="pkfzzlbbg"/><path class="jwxgs0b2c"/><path class="v4hj5197o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reading-light-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwxgs0b2c {
  d: path("m11 9 4 -4");
}

.pkfzzlbbg {
  d: path("M11 9v11");
}

.v4hj5197o {
  d: path("M10 9h8l-4 4Z");
}

.y--9wccrh {
  d: path("M5 20h12");
}

</style>
