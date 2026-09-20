<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG3rMndcyG" class="ht3z8-bqi"/></defs><clipPath id="SVGBOv6peZo"><use href="#SVG3rMndcyG"/></clipPath><path clip-path="url(#SVGBOv6peZo)" class="afn2uub7d"/><g clip-path="url(#SVGBOv6peZo)"><path class="amj0lfb9p"/><path class="rer4t6fbz"/><path class="i3j607fle"/><path class="ye_aqok4z"/><path class="shnfmd4id"/><path class="jvg3qda9u"/><path class="f_pwjknnq"/><path class="zybx-6hav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:rescue-workers-helmet" /></template>
<style>
.afn2uub7d {
  fill: var(--svg-color--37b4e2, #37b4e2);
  d: path("M64.71 11.75h.19h-.36z");
}

.amj0lfb9p {
  fill: var(--svg-color--875e54, #875e54);
  d: path("M64.71 123.92c-31.32 0-56.79-25.3-56.79-56.4s25.48-56.4 56.79-56.4s56.79 25.3 56.79 56.4s-25.47 56.4-56.79 56.4m0-107.06c-28.42 0-51.55 22.73-51.55 50.67s23.12 50.66 51.55 50.66c28.42 0 51.55-22.73 51.55-50.66c0-27.94-23.12-50.67-51.55-50.67");
}

.f_pwjknnq {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M7.64 53.05s-4.58 2.74-5.05 7.02l3.87 1.59zm112.74-.72s4.25 2.42 5.05 7.78l-3.87 1.59z");
}

.ht3z8-bqi {
  d: path("M0 0h128v128H0z");
}

.i3j607fle {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M125.41 60.07c-.03-.37-2.27.22-3.41-3.87c-3.98-14.23-15.58-48.67-57.99-48.67l-.01.95l-.01-.95c-42.53 0-52.97 33.14-56.94 47.64c-1.23 4.47-4.42 4.51-4.46 4.91c-.34 3.7 3.44 8.92 11.81 14.07c12.4 7.62 33.65 11.72 49.59 11.73h.02c15.94 0 37.19-4.11 49.59-11.73c8.37-5.15 12.15-10.37 11.81-14.08");
}

.jvg3qda9u {
  fill: var(--svg-color--fff, #fff);
  d: path("M50.62 41.79h26.76v7.81H50.62z");
}

.rer4t6fbz {
  fill: var(--svg-color--875e54, #875e54);
  d: path("M54.03 112.3h20.32v10.03H54.03z");
}

.shnfmd4id {
  fill: var(--svg-color--fff, #fff);
  d: path("M60.65 32.86h6.69v24.53h-6.69z");
}

.ye_aqok4z {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("m53.23 7.3l1.09-.32c6.3-1.84 13.01-1.73 19.25.32l13.16 56.29l-.3.06a111.8 111.8 0 0 1-44.81.01l-.35-.07z");
}

.zybx-6hav {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("m125.43 60.4l-7.49 2.27C81.52 73.33 44.1 73.12 7.74 62.05l-5.17-1.56l.18-1.11a3.68 3.68 0 0 1 4.76-2.9l.23.07c36.36 11.07 73.79 11.28 110.2.62l2.69-.82c2.08-.63 4.24.71 4.6 2.85z");
}

</style>
