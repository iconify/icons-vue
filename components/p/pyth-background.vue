<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uiqsnqbcc"/><path class="sarn5lszf"/><path class="u3raiaccu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pyth-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sarn5lszf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.372 10.4c0 .882-.76 1.371-1.372 1.371V13.6a3.2 3.2 0 1 0-3.2-3.2v7.863L10.63 20v-9.6c0-.594.489-1.371 1.371-1.371a1.37 1.37 0 0 1 1.371 1.371");
}

.u3raiaccu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a6.37 6.37 0 0 0-4.8 2.167A6.38 6.38 0 0 0 5.6 10.4v4.8l1.829 1.76V10.4c0-2.386 1.92-4.571 4.57-4.571c2.652 0 4.572 2.207 4.572 4.57c0 2.652-2.185 4.572-4.571 4.572v1.828A6.4 6.4 0 1 0 12 4");
}

.uiqsnqbcc {
  fill: var(--svg-color--110f24, #110f24);
  d: path("M24 0H0v24h24z");
}

</style>
