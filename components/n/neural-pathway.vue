<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko57swbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neural-pathway" /></template>
<style>
.ko57swbdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.75c.5-2 2.75-3 4.75-2.25c1.25-1.25 4-1 5 .5c2.25 0 3.75 1.75 3.5 3.75c1.5 1.25 1.5 3.75.25 5c.25 2.25-1.5 3.75-3.5 3.5c-1 1.5-3.5 2-5 1c-1.75 1-4.25.5-5-1c-2.25.25-4-1.5-3.5-3.5C2.25 11.5 2.25 9 3.75 8c0-1.75 1.5-2.75 3.25-2.25Zm7.75 12l.75 3.75M4.75 13h.01M7 10.5h.01m2.49-1h.01m2.49 1h.01M14.25 9h.01m2.24-1.5h.01M19 6.75h.01");
}

</style>
