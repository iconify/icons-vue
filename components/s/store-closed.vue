<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jksggizrl"/><path class="xjxj4ykqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-closed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jksggizrl {
  d: path("M3 7.5L4.5 3h15L21 7.5M4.5 10.75V21m15-10.25V21");
}

.xjxj4ykqy {
  d: path("M3 7.5a4.5 4.5 0 0 0 9 0a4.5 4.5 0 0 0 9 0m-9 0v7m-3 0h6a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 15 20H9a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 9 14.5m.75 2.75h4.5");
}

</style>
