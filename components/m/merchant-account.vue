<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dg9edpbsx"/><path class="hofeaufsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:merchant-account" /></template>
<style>
.dg9edpbsx {
  d: path("m3 9l2-5.5h14L21 9M4.5 11.25v9.25h15v-9.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hofeaufsq {
  d: path("M3 9a2.25 2.25 0 0 0 4.5 0A2.25 2.25 0 0 0 12 9a2.25 2.25 0 0 0 4.5 0A2.25 2.25 0 0 0 21 9M7.5 9l.75-5.5M16.5 9l-.75-5.5M10 20.5V15h4v5.5");
}

</style>
