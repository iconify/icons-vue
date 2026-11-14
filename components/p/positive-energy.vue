<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgdo4gf4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:positive-energy" /></template>
<style>
.vgdo4gf4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.939 5.663l-3.961 4.893A1.5 1.5 0 0 0 6.144 13h1.568a1.5 1.5 0 0 1 1.477 1.761L8.75 17.25a1.063 1.063 0 0 0 1.889.835l3.993-5.168a1.5 1.5 0 0 0-1.187-2.417h-1.638a1.5 1.5 0 0 1-1.474-1.776L10.75 6.5a1.029 1.029 0 0 0-1.811-.837M18 15v6m-3-3h6");
}

</style>
