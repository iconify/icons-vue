<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea_3mebbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-bath-time" /></template>
<style>
.ea_3mebbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.75h19m-17.5 0v2.75A4.5 4.5 0 0 0 8.5 19h7a4.5 4.5 0 0 0 4.5-4.5v-2.75M7.5 19l-.75 2.25M16.5 19l.75 2.25M4.5 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5.75-2.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM16 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
