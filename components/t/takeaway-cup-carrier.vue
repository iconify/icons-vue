<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-4y-ubqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:takeaway-cup-carrier" /></template>
<style>
.f-4y-ubqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19l-2 5.5h-15ZM5 9h5.5l-.5 5H5.5Zm8.5 0H19l-.5 5H14ZM4.25 6.5h7V9h-7Zm8.5 0h7V9h-7Zm-5 0v-2m8.5 2v-2");
}

</style>
