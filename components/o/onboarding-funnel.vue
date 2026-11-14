<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x217mfbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:onboarding-funnel" /></template>
<style>
.x217mfbdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.15 3.5h5.7a2.356 2.356 0 0 1 1.9 3.75l-2.242 3.057A2.63 2.63 0 0 0 12 11.859v5.405a1.382 1.382 0 0 1-2 1.236l-.549-.274A2.63 2.63 0 0 1 8 15.878v-4.019a2.63 2.63 0 0 0-.508-1.552L5.25 7.25a2.356 2.356 0 0 1 1.9-3.75m9.1 12.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M14.5 21.5C14.5 20 16 19 18 19s3.5 1 3.5 2.5");
}

</style>
