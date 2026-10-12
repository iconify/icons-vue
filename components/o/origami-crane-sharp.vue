<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m6-583bki"/><path class="jabgvkbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:origami-crane-sharp" /></template>
<style>
.jabgvkbdq {
  d: path("m9.99 14.06l5.77-10.62L16 3l.39.31l1.72 1.38l.39.31l-.18.47l-3.64 9.56l-.18.47l-.49-.1l-3.77-.8l-.49-.1z");
}

.m6-583bki {
  d: path("m3.04 6.1l1.42-1.95l.29-.4l.38.32l.74.61l.38.32l.17.47l3.16 8.56l.17.47l.49.1l3.77.8l.49.1l.43-.25l5.89-3.5l.43-.25l-.22.45l-3.56 7.1l-.22.45H8.5l-.2-.46L2.95 6.96l-.2-.46z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
