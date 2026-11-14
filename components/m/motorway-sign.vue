<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v8ktjwwza"/><path class="ex51uob0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motorway-sign" /></template>
<style>
.ex51uob0j {
  d: path("M12 11.5v-6M9.5 8L12 5.5L14.5 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8ktjwwza {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 11V6A3.5 3.5 0 0 1 6 2.5m1 12v7m10-7v7");
}

</style>
