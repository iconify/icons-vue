<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyntq_bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-moon-round" /></template>
<style>
.dyntq_bop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 15a6 6 0 1 1-6-6a4.269 4.269 0 1 0 6 6m-1.974-5.82a3 3 0 0 1 1.793 1.794M19 12h2m-9-7V3m4.95 4.05l1.414-1.414");
}

</style>
