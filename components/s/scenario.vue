<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znl6zsm3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scenario" /></template>
<style>
.znl6zsm3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 6.5h7.181a1.75 1.75 0 0 1 1.029.335l.915.665a1.236 1.236 0 0 1 0 2l-.915.665a1.75 1.75 0 0 1-1.029.335H10.75A1.75 1.75 0 0 1 9 8.75v-.5a1.75 1.75 0 0 1 1.75-1.75m2.5 6H6.069a1.75 1.75 0 0 0-1.029.335l-.915.665a1.236 1.236 0 0 0 0 2l.915.665a1.75 1.75 0 0 0 1.029.335h7.181A1.75 1.75 0 0 0 15 14.75v-.5a1.75 1.75 0 0 0-1.75-1.75M12 2.5v4M9.75 4.75L12 2.5l2.25 2.25M12 10.5v2m0 4v5");
}

</style>
