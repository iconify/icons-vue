<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="ic_c3bd4p"/><path clip-rule="evenodd" class="dc88v3ssj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mm-background" /></template>
<style>
.dc88v3ssj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.706 8.236v7.53h-.47V9.648l-1.883 2.307v3.81h-3.796l3.325-4.068V9.721l-2.962 3.666L7.765 9.72v6.046h-.471v-7.53l3.628 4.271l3.43-4.27v2.896zm-2.824 4.294l-2.268 2.765h2.268z");
}

.ft5dv1b6b {
  fill: none;
}

.ic_c3bd4p {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.47a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 1 0 0 15.06");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
