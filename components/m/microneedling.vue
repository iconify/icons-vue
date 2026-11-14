<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3tqtrb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microneedling" /></template>
<style>
.q3tqtrb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 5.5h9.5a2.75 2.75 0 0 1 2.75 2.75A2.75 2.75 0 0 1 16.75 11h-9.5A2.75 2.75 0 0 1 4.5 8.25A2.75 2.75 0 0 1 7.25 5.5M12 11v3m0 0za2 2 0 0 1 2 2v3.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V16a2 2 0 0 1 2-2M8.5 2.5v3m3.5-3v3m3.5-3v3");
}

</style>
