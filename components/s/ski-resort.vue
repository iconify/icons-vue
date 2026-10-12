<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk4ubbbrl"/><path class="cvx864bpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ski-resort" /></template>
<style>
.cvx864bpd {
  d: path("m6.75 9.5l1.75 1.25l1.5-1.5l1.75 1.5M8 21.25l8-3.5m-8 0l8 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk4ubbbrl {
  d: path("m3.37 14.17l5.51-9.59q.62-1.08 1.26-.01l2.47 4.11q.64 1.07 1.38.06l.52-.73q.74-1.01 1.48 0l4.52 6.23q.74 1.01-.51 1.01H4q-1.25 0-.63-1.08");
}

</style>
