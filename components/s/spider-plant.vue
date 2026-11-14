<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="or2erdbgb"/><path class="c-oie0b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spider-plant" /></template>
<style>
.c-oie0b8o {
  d: path("M12 15.5c2-7 6.5-8.5 8-4.5v5m-1.5 2.5L20 16l1.5 2.5");
}

.or2erdbgb {
  d: path("M8 15.5h8l-1 6H9Zm4 0c-2-7-6.5-8.5-9-3m9 3c0-5.5.5-10 2.5-12.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
