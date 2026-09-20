<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qfzgigbia"/><path class="cbp5n6ava"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:somm-background" /></template>
<style>
.cbp5n6ava {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 7.331A3.33 3.33 0 0 0 15.331 4H8.67A3.33 3.33 0 0 0 12 7.331m-8 8V8.67a3.332 3.332 0 0 1 0 6.662m8 .098c1.84 0 3.429-1.589 3.429-3.429S13.84 8.571 12 8.571S8.571 10.16 8.571 12S10.16 15.429 12 15.429M16.669 12A3.33 3.33 0 0 0 20 15.331V8.67A3.33 3.33 0 0 0 16.669 12M20 4v3.331A3.33 3.33 0 0 1 16.669 4zM4 7.331A3.33 3.33 0 0 0 7.331 4H4zm5.646 10.315A3.33 3.33 0 0 1 15.33 20H8.67c0-.886.348-1.731.971-2.354zM16.669 20H20v-3.331A3.33 3.33 0 0 0 16.669 20M4 20v-3.331A3.33 3.33 0 0 1 7.331 20z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qfzgigbia {
  fill: var(--svg-color--f26057, #f26057);
  d: path("M24 0H0v24h24z");
}

</style>
