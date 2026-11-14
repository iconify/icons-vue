<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjywkqbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sla-warning" /></template>
<style>
.zjywkqbzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h11m-11 19h6.4m-4.4-19C6.5 8 10 9.5 10 12s-3.5 4-3.5 9.5m7-19c0 5.5-3.5 7-3.5 9.5c0 1.845 1.906 3.145 2.905 5.91M18 14.25l3.75 7h-7.5Zm0 4.5h.01");
}

</style>
