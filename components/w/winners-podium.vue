<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzjp2h-8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:winners-podium" /></template>
<style>
.kzjp2h-8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21v-6.5h6V10h7v6.5h6V21ZM12 2.75l.735 1.489l1.643.238l-1.189 1.159l.28 1.637L12 6.5l-1.469.773l.28-1.637l-1.189-1.159l1.643-.238Z");
}

</style>
