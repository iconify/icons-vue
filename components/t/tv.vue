<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g41uuudiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tv" /></template>
<style>
.g41uuudiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 11C2 9.3431 3.3431 8 5 8L19 8C20.6569 8 22 9.3431 22 11L22 18C22 19.6569 20.6569 21 19 21L5 21C3.3431 21 2 19.6569 2 18L2 11ZM8 3L12 8L16 3");
}

</style>
