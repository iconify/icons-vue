<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b49r-bcwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pushpin" /></template>
<style>
.b49r-bcwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.48 5.459l1.061 1.061a1.75 1.75 0 0 1 0 2.475l-1.938 1.938a1.75 1.75 0 0 0-.471.857l-.612 2.755a1.75 1.75 0 0 1-2.946.858l-3.977-3.977a1.75 1.75 0 0 1 .858-2.946l2.755-.612a1.75 1.75 0 0 0 .857-.471l1.938-1.938a1.75 1.75 0 0 1 2.475 0m-6.894 7.955l-4.95 4.95");
}

</style>
