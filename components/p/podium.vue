<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjnp3ebfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podium" /></template>
<style>
.fjnp3ebfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5v-7h6V10h7v5.5h6v5ZM12 3.25l.735 1.489l1.643.238l-1.189 1.159l.28 1.637L12 7l-1.469.773l.28-1.637l-1.189-1.159l1.643-.238Z");
}

</style>
