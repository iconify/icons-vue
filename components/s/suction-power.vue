<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpp2jnxoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:suction-power" /></template>
<style>
.rpp2jnxoa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.5h16V18a2 2 0 0 0-2-2h-4v-3.5h-4V16H6a2 2 0 0 0-2 2Zm8-18V8m-1.75-1.75L12 8l1.75-1.75M3.5 4.5l4 4m-3 0h3v-3m13-1l-4 4m3 0h-3v-3");
}

</style>
