<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="pch7edc8w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pch7edc8w {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.55 16.5c-.115.29-1.51 1.5-2.965 1.5C10.425 18 9 17.215 9 15.65c0-1.44 1.8-2.13 4.01-2.93c2.665-.9 3.99-2.49 3.99-4.67C17 5.45 14.89 4 11.72 4c-1.675 0-3.82.87-4.385 1.45L8.665 7c.535-.275 1.55-1 3.035-1c2.225 0 3.3.995 3.3 2.05c0 1.445-.815 2.11-3.07 2.935C9.17 12 7 13.22 7 15.49C7 17.88 8.73 20 12.585 20c1.575 0 3.4-.87 4.415-1.94z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
