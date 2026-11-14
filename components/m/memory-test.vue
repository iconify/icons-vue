<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s94cy3bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:memory-test" /></template>
<style>
.s94cy3bji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 5zA1.25 1.25 0 0 1 4.5 6.25v11.5A1.25 1.25 0 0 1 3.25 19A1.25 1.25 0 0 1 2 17.75V6.25A1.25 1.25 0 0 1 3.25 5m6.125 0h.25a2.625 2.625 0 0 1 2.625 2.625v8.75A2.625 2.625 0 0 1 9.625 19h-.25a2.625 2.625 0 0 1-2.625-2.625v-8.75A2.625 2.625 0 0 1 9.375 5m6.375 0zA1.25 1.25 0 0 1 17 6.25v11.5A1.25 1.25 0 0 1 15.75 19a1.25 1.25 0 0 1-1.25-1.25V6.25A1.25 1.25 0 0 1 15.75 5m4.75 0za1.25 1.25 0 0 1 1.25 1.25v11.5A1.25 1.25 0 0 1 20.5 19a1.25 1.25 0 0 1-1.25-1.25V6.25A1.25 1.25 0 0 1 20.5 5m-11 5.25h.01m-.01 3.5h.01");
}

</style>
