<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p18111bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-distort" /></template>
<style>
.p18111bts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3H6C6.5523 3 7 3.4477 7 4V6C7 6.5523 6.5523 7 6 7H4C3.4477 7 3 6.5523 3 6V4C3 3.4477 3.4477 3 4 3ZM18 6H20C20.5523 6 21 6.4477 21 7V9C21 9.5523 20.5523 10 20 10H18C17.4477 10 17 9.5523 17 9V7C17 6.4477 17.4477 6 18 6ZM16 17H18C18.5523 17 19 17.4477 19 18V20C19 20.5523 18.5523 21 18 21H16C15.4477 21 15 20.5523 15 20V18C15 17.4477 15.4477 17 16 17ZM6 13H8C8.5523 13 9 13.4477 9 14V16C9 16.5523 8.5523 17 8 17H6C5.4477 17 5 16.5523 5 16V14C5 13.4477 5.4477 13 6 13ZM7 5L17 8M19 10L17 17M15 19L9 15M7 13L5 7");
}

</style>
