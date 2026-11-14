<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc2h3guji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:whistleblower" /></template>
<style>
.cc2h3guji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9.5h1.203a1.75 1.75 0 0 0 .996-.311l3.305-2.288A1.75 1.75 0 0 1 12.5 8.34v7.32a1.75 1.75 0 0 1-2.746 1.439l-3.305-2.288a1.75 1.75 0 0 0-.996-.311H4.25a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 4.25 9.5m10.931.25a3.5 3.5 0 0 1 0 4.5m2.107-6.267a6.25 6.25 0 0 1 0 8.034m2.106-9.802a9 9 0 0 1 0 11.57");
}

</style>
