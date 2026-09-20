<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o333ol9pg"/><path class="pyqflqb6u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o333ol9pg {
  fill: var(--svg-color--00e13a, #00e13a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pyqflqb6u {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.53 18.155a6.2 6.2 0 0 1-4.052-1.967A6.12 6.12 0 0 1 5.882 12c0-1.553.542-3.05 1.596-4.188a6.2 6.2 0 0 1 4.051-1.967V4A8.04 8.04 0 0 0 4 12a8.005 8.005 0 0 0 7.53 8zm1.835-5.59q.471.1.47.404q0 .319-.419.518a3 3 0 0 1-1.195.198q-1.41.001-2.71-.796l-.683.838c.804.54 1.735.863 2.701.937v2.498a5.19 5.19 0 0 1 0-10.33v2.486c-.7.047-1.28.188-1.694.428c-.494.296-.743.696-.743 1.21q.002.746.743 1.105c.466.226 1.21.363 2.245.405c.682.028 1.115.061 1.29.094zm2.466-4.052a5.2 5.2 0 0 1 0 6.974a5.24 5.24 0 0 1-3.36 1.68v-2.485c.809-.033 1.458-.188 1.92-.46a1.46 1.46 0 0 0 .771-1.309c0-.49-.197-.857-.588-1.092q-.544-.338-1.788-.456a40 40 0 0 0-1.087-.062a4.5 4.5 0 0 1-.861-.094q-.446-.105-.447-.367q0-.542 1.623-.54c.79 0 1.563.197 2.259.578l.706-.824a5.1 5.1 0 0 0-2.508-.738V6.833a5.22 5.22 0 0 1 3.36 1.675zm-3.36-2.668V4A8.03 8.03 0 0 1 20 12a8.01 8.01 0 0 1-7.53 8v-1.845a6.16 6.16 0 0 0 4.048-1.967c1.058-1.139 1.6-2.635 1.6-4.188s-.542-3.05-1.6-4.188a6.2 6.2 0 0 0-4.047-1.967");
}

</style>
