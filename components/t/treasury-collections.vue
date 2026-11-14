<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u0h9gpkxs"/><path class="dawc-hbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-collections" /></template>
<style>
.dawc-hbdd {
  d: path("M13 5.75c0-.42-.43-.63-1-.75c-.7.12-1.12.47-1 1c-.12 1.05 2.12.6 2 2c.12.5-.35.88-1 1c-.6-.12-1.03-.38-1-.75m1-4V5m0 4v.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u0h9gpkxs {
  d: path("M2.5 14h5L9 16.5h6l1.5-2.5h5v5.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Zm5.25-7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

</style>
