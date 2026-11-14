<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uqprg0xqf"/><path class="pakilwbpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:species-label" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pakilwbpr {
  d: path("M12 7.5c0-3 2.5-4.5 5-5m-6.5 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M9.5 14h5m-5 3.5h5");
}

.uqprg0xqf {
  d: path("m7.269 7.231l1.462-1.462A2.63 2.63 0 0 1 10.587 5h2.826a2.63 2.63 0 0 1 1.856.769l1.462 1.462a2.63 2.63 0 0 1 .769 1.856v9.788a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 18.875V9.087a2.63 2.63 0 0 1 .769-1.856");
}

</style>
