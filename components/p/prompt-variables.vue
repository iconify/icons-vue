<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4qm_vxou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prompt-variables" /></template>
<style>
.c4qm_vxou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5H8A2.5 2.5 0 0 0 5.5 6v3.75A2.25 2.25 0 0 1 3.25 12a2.25 2.25 0 0 1 2.25 2.25V18A2.5 2.5 0 0 0 8 20.5h.5m7-17h.5A2.5 2.5 0 0 1 18.5 6v3.75A2.25 2.25 0 0 0 20.75 12a2.25 2.25 0 0 0-2.25 2.25V18a2.5 2.5 0 0 1-2.5 2.5h-.5M10 12h4");
}

</style>
