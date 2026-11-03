<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adhjd9buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:utensils-sharp" /></template>
<style>
.adhjd9buj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 2C17.6568 2 19 3.7909 19 6C19 8.2091 17.6568 10 16 10C14.3431 10 13 8.2091 13 6C13 3.7909 14.3431 2 16 2ZM5 13L9 13L9 8.862C9 6.1485 7.6021 3.6263 5.301 2.1881L5 2L5 2.355L5 13ZM16 10L16 23M5 13L5 23");
}

</style>
