<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ymhlmhmkw"/><path class="utzqci34y"/><path class="yte71vedb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:med-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utzqci34y {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.605 6.948c.4-.875 1.13-1.19 1.81-.78c.935.56.5 1.485.295 2.015l-3.36 8.99c-.385.745-1.06 1.05-1.725.68c-.67-.375-.68-1.21-.4-1.835c1.32-2.965 3.075-8.4 3.38-9.07m-9.841-.149c.27-.655 1.1-.88 1.63-.62c.84.415.685 1.155.505 1.68l-3.825 9.575c-.365.57-1.04.715-1.535.405c-.605-.38-.59-1.26-.48-1.605c1.16-2.94 3.435-8.77 3.7-9.43zm5.286-.125c.19-.445.92-.825 1.43-.5c.625.39.565 1.135.445 1.46l-1.975 5.05c-.325.65-.955 1.015-1.59.65c-.63-.375-.46-1.145-.3-1.525l1.985-5.135z");
}

.ymhlmhmkw {
  fill: var(--svg-color--2073e9, #2073e9);
  d: path("M24 0H0v24h24z");
}

.yte71vedb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.75 8.498a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M15.25 18a1.25 1.25 0 1 0 0-2.501a1.25 1.25 0 0 0 0 2.5");
}

</style>
