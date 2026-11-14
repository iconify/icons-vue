<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb9kxtazo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snowboarder-rail" /></template>
<style>
.nb9kxtazo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.338 7.152l12.803-2.258a1.5 1.5 0 0 1 1.737 1.217a1.5 1.5 0 0 1-1.216 1.737L5.859 10.106a1.5 1.5 0 0 1-1.737-1.217a1.5 1.5 0 0 1 1.216-1.737M3 14h18M6 14v6m12-6v6");
}

</style>
