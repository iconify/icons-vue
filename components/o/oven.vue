<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8vfc1bcj"/><path clip-rule="evenodd" class="bzoga7-av"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:oven" /></template>
<style>
.bzoga7-av {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 6C9 6.5523 8.5523 7 8 7C7.4477 7 7 6.5523 7 6C7 5.4477 7.4477 5 8 5C8.5523 5 9 5.4477 9 6ZM13 6C13 6.5523 12.5523 7 12 7C11.4477 7 11 6.5523 11 6C11 5.4477 11.4477 5 12 5C12.5523 5 13 5.4477 13 6ZM17 6C17 6.5523 16.5523 7 16 7C15.4477 7 15 6.5523 15 6C15 5.4477 15.4477 5 16 5C16.5523 5 17 5.4477 17 6Z");
  stroke: none;
}

.c8vfc1bcj {
  d: path("M8 2L16 2C18.2091 2 20 3.7909 20 6L20 20C20 21.1046 19.1046 22 18 22L6 22C4.8954 22 4 21.1046 4 20L4 6C4 3.7909 5.7909 2 8 2ZM4 10L20 10M9 14L15 14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
