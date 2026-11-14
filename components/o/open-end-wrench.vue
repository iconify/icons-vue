<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7mtd0noo"/><path class="ohnwtobsr"/><path class="msji34bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-end-wrench" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7mtd0noo {
  d: path("M16.773 3.338za1.25 1.25 0 0 1 0 1.768l-.53.53a1.5 1.5 0 0 0 0 2.121a1.5 1.5 0 0 0 2.121 0l.53-.53a1.25 1.25 0 0 1 1.768 0a1.25 1.25 0 0 1 0 1.768l-2.386 2.386a1.75 1.75 0 0 1-1.485.495l-1.032-.147a1.75 1.75 0 0 1-.989-.495L12.766 9.23a1.75 1.75 0 0 1-.495-.989l-.147-1.032a1.75 1.75 0 0 1 .495-1.485l2.386-2.386a1.25 1.25 0 0 1 1.768 0");
}

.msji34bis {
  d: path("M3.338 16.773za1.25 1.25 0 0 0 1.768 0l.53-.53a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-.53.53a1.25 1.25 0 0 0 0 1.768a1.25 1.25 0 0 0 1.768 0l2.386-2.386a1.75 1.75 0 0 0 .495-1.485l-.147-1.032a1.75 1.75 0 0 0-.495-.989L9.23 12.766a1.75 1.75 0 0 0-.989-.495l-1.032-.147a1.75 1.75 0 0 0-1.485.495l-2.386 2.386a1.25 1.25 0 0 0 0 1.768");
}

.ohnwtobsr {
  d: path("m13.591 10.055l.354.354a1.5 1.5 0 0 1 0 2.121l-1.415 1.415a1.5 1.5 0 0 1-2.121 0l-.354-.354a1.5 1.5 0 0 1 0-2.121l1.415-1.415a1.5 1.5 0 0 1 2.121 0");
}

</style>
