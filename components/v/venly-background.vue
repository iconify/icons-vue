<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGjj1agnIh)" class="r4i437pya"/><path class="oi4rolewi"/></g><defs><linearGradient id="SVGjj1agnIh" x1="10.457" x2="20.842" y1="4.8" y2="7.697" gradientUnits="userSpaceOnUse"><stop class="bmjwc1blo"/><stop offset="1" class="xmdw4_btk"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:venly-background" /></template>
<style>
.bmjwc1blo {
  stop-color: var(--svg-color--7735e8, #7735e8);
}

.ft5dv1b6b {
  fill: none;
}

.oi4rolewi {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.844 9.516l-1.962.727c-.083.03-.163-.049-.128-.13l2.188-5.178a.098.098 0 0 0-.125-.129l-4.158 1.42a.3.3 0 0 0-.177.166l-2.818 6.934c-.035.088.053.176.143.144l1.76-.63c.097-.033.187.07.135.16l-2.585 4.28a.147.147 0 0 1-.25 0l-2.585-4.283c-.053-.088.035-.193.135-.159l1.76.63c.09.031.177-.056.142-.144L8.5 6.392a.3.3 0 0 0-.177-.166L4.17 4.806a.099.099 0 0 0-.125.13l2.185 5.178c.033.078-.047.159-.127.13l-1.95-.728c-.1-.036-.19.069-.135.159l5.805 9.376c.057.093.16.149.272.149H13.9c.11 0 .215-.056.273-.149l5.815-9.376c.047-.09-.043-.195-.143-.159");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xmdw4_btk {
  stop-color: var(--svg-color--c62cf1, #c62cf1);
}

</style>
