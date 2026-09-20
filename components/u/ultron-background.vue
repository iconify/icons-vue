<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGwW6I4bOk)" class="r4i437pya"/><path class="zytwf9ngn"/></g><defs><linearGradient id="SVGwW6I4bOk" x1="4" x2="20" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="ov87g3b_i"/><stop offset="1" class="ghqnkmbsh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ultron-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ghqnkmbsh {
  stop-color: var(--svg-color--8c47f5, #8c47f5);
}

.ov87g3b_i {
  stop-color: var(--svg-color--1fffa3, #1fffa3);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zytwf9ngn {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.346 11.998c0 1.656-.75 2.997-1.672 2.997S4 13.654 4 11.998S4.75 9 5.672 9s1.671 1.342 1.671 2.998m1.538 0a5.1 5.1 0 0 1-.232 1.553a5.3 5.3 0 0 1-.647 1.332c-.168.25-.53.808-.225 1.022a.5.5 0 0 0 .218.077c.59.083 1.13-.284 1.528-.658a4.5 4.5 0 0 0 1.023-1.43a4.68 4.68 0 0 0 0-3.788a4.5 4.5 0 0 0-1.023-1.43c-.398-.374-.941-.74-1.528-.657a.5.5 0 0 0-.218.076c-.307.214.057.772.225 1.022c.278.412.496.862.647 1.332a5.1 5.1 0 0 1 .232 1.553m3.61 0c0 .687-.101 1.373-.3 1.99a7 7 0 0 1-.829 1.706c-.215.32-.68 1.034-.287 1.308a.65.65 0 0 0 .278.098c.754.107 1.449-.365 1.959-.844a5.8 5.8 0 0 0 1.31-1.83a6.06 6.06 0 0 0 0-4.856a5.7 5.7 0 0 0-1.31-1.83c-.51-.478-1.205-.95-1.96-.843a.6.6 0 0 0-.277.098c-.393.274.072.989.287 1.308c.355.529.635 1.105.829 1.706c.199.617.3 1.303.3 1.99m4.198 0a8.2 8.2 0 0 1-.374 2.488a8.5 8.5 0 0 1-1.034 2.132c-.269.4-.848 1.294-.36 1.637a.8.8 0 0 0 .348.122c.943.133 1.81-.455 2.45-1.056a7.2 7.2 0 0 0 1.638-2.29a7.5 7.5 0 0 0 0-6.07a7.2 7.2 0 0 0-1.638-2.29c-.637-.6-1.507-1.19-2.448-1.056a.8.8 0 0 0-.347.122c-.491.343.09 1.236.359 1.637a8.6 8.6 0 0 1 1.035 2.132c.249.772.373 1.63.373 2.488");
}

</style>
