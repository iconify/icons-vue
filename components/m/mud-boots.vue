<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rxzetz7iq"/><path class="eclr8n6cx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mud-boots" /></template>
<style>
.eclr8n6cx {
  d: path("M5.5 14c1.5 1.5 3-1 4.5.5c1 1 2-.5 3.5-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxzetz7iq {
  d: path("M7.25 3h3.5a1.75 1.75 0 0 1 1.75 1.75v7.168a1.75 1.75 0 0 0 .967 1.566l3.663 1.831a1.75 1.75 0 0 1 .618.515l.902 1.203a1.75 1.75 0 0 1 .35 1.05V19a1.5 1.5 0 0 1-1.5 1.5H7.25a1.75 1.75 0 0 1-1.75-1.75v-14A1.75 1.75 0 0 1 7.25 3M5.5 6h7");
}

</style>
