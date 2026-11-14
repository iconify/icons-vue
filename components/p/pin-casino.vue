<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xuak0wb0i"/><path class="rs2m_ibzx"/><path class="rocnkmbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-casino" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rocnkmbpf {
  d: path("M15.75 4.5h.01M19 7.75h.01M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

.rs2m_ibzx {
  fill: currentColor;
  d: path("m7.596 13.595l.348.325a1.5 1.5 0 0 1 .358 1.683l-.186.438a1.068 1.068 0 0 1-1.712.364l-.348-.325a1.5 1.5 0 0 1-.358-1.683l.186-.438a1.068 1.068 0 0 1 1.712-.364");
}

.xuak0wb0i {
  d: path("m3.815 9.032l3.668-.78a2.625 2.625 0 0 1 3.113 2.022l1.611 7.581a2.625 2.625 0 0 1-2.022 3.113l-3.668.78a2.625 2.625 0 0 1-3.113-2.022l-1.611-7.581a2.625 2.625 0 0 1 2.022-3.113M16.375 2.5h2A2.625 2.625 0 0 1 21 5.125v2a2.625 2.625 0 0 1-2.625 2.625h-2a2.625 2.625 0 0 1-2.625-2.625v-2A2.625 2.625 0 0 1 16.375 2.5");
}

</style>
