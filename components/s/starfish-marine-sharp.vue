<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2fzyvb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starfish-marine-sharp" /></template>
<style>
.x2fzyvb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.44 3.65l1.62 3.26l.44.9l.92.39l4.1 1.7l.92.38l-.88.46l-2.63 1.36l-.89.46l.17.99l.62 3.59l.17.99l-.89-.47l-3.22-1.69l-.89-.47l-.97.23l-4.32 1.03l-.97.24l.45-.9l1.32-2.64l.45-.9l-.72-.69l-2.61-2.55l-.71-.7l.99-.14l3.6-.52l.99-.15l.44-.9l1.62-3.26l.44-.9zM12 6.5h.01m4.71 4.21h.01m-1.94 4.38h.01m-6.3-.63h.01M7.48 9.78h.01M2.75 21l3.611-1.083L9.25 21m5.5 0l3.611-1.083L21.25 21");
}

</style>
