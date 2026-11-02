<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmqs1zb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thermometer-round" /></template>
<style>
.hmqs1zb5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12V5a2 2 0 1 1 4 0v7a4.472 4.472 0 1 1-4 0m8-8h4m-4 3h2m-2 3h4");
}

</style>
