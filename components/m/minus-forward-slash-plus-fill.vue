<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3-4d-lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:minus-forward-slash-plus-fill" /></template>
<style>
.ad3-4d-lf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 18H17.9986M17.9986 18H22M17.9986 18L17.9971 22M17.9986 18L18 14M2 6H10M5 22L19 2");
}

</style>
