<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="loeivvbxf"/><path class="s_1s2180y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vine-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.loeivvbxf {
  fill: var(--svg-color--00b488, #00b488);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s_1s2180y {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.667 19.987c-.634-.1-1.167-.568-1.9-1.302C7.567 16.615 5.3 11.075 5 6.403h2.667c.7 4.906 1.8 8.244 4.166 10.947c1.167-1.101 2.134-2.637 2.8-3.871c-1.3-.601-2.033-1.736-2.433-2.77C10.967 7.503 12.033 4.1 15.533 4C18.1 4 18.967 5.936 19 7.771a8.4 8.4 0 0 1-.533 2.804c-.734.167-1.5-.034-1.967-.367c-.367-.267-.5-.134-.267-.868c.267-.934.367-2.97-.9-3.004c-.866.067-1.1 1.135-1.1 1.87c.234 3.003 2.167 4.338 4.734 3.67v1.936c-.834.2-.867.2-1.9.234c-.6 1.402-3.867 6.241-5.434 5.94z");
}

</style>
