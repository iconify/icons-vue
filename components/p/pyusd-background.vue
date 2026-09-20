<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wwwl8dbau"/><path clip-rule="evenodd" class="vo72yj95x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pyusd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vo72yj95x {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.705 4.576A.656.656 0 0 1 8.355 4h5.995a4.91 4.91 0 0 1 4.56 5.387c-.293 3.877-3.35 5.28-4.944 5.28h-2.09l-.891 4.79a.654.654 0 0 1-.65.543H6.376a.67.67 0 0 1-.656-.757L6.708 12h-.982a.66.66 0 0 1-.661-.667c0-.368.293-.666.661-.666H6.89L7.246 8h-1.52a.66.66 0 0 1-.661-.667c0-.368.288-.666.656-.666h1.701zM8.575 8l-.363 2.667h4.762a1.28 1.28 0 0 0 1.323-1.334A1.28 1.28 0 0 0 12.974 8zm-.54 4h4.94a2.613 2.613 0 0 0 2.64-2.667c0-1.493-1.142-2.666-2.64-2.666h-4.22l.177-1.334h5.333a3.573 3.573 0 0 1 3.328 3.947c-.23 3.056-2.587 4.053-3.627 4.053h-2.64c-.32 0-.587.23-.65.544l-.886 4.79H7.134z");
}

.wwwl8dbau {
  fill: var(--svg-color--3b6fef, #3b6fef);
  d: path("M24 0H0v24h24z");
}

</style>
