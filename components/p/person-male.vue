<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mza3a9byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-male" /></template>
<style>
.mza3a9byz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 21v-4a4.5 4.5 0 0 1 9 0v4m3-3.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM18.75 16l2.75-2.75m-3 0h3v3");
}

</style>
