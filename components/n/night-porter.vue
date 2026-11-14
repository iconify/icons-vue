<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k8foptb4o"/><path class="qw4v_e26l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:night-porter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8foptb4o {
  d: path("M2.5 3h2v15H12");
}

.qw4v_e26l {
  d: path("M9.75 8za2.5 2.5 0 0 1 2.5 2.5v5a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5v-5A2.5 2.5 0 0 1 9.75 8M8.5 8V5H11v3M5.5 20.75h.01m5.49 0h.01m7.99-6A3.5 3.5 0 1 0 21.75 19A2.75 2.75 0 0 1 19 14.75");
}

</style>
