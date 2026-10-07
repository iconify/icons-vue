<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffubp449w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:notebook-pen-sharp" /></template>
<style>
.ffubp449w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 11.1317L20 22L4 22L4 2L14.8683 2M1 7L7 7M1 12L7 12M1 17L7 17M11.5 12.5L15.6248 10.8501L21.4874 4.9874C22.1709 4.304 22.1709 3.196 21.4874 2.5126C20.804 1.8291 19.696 1.8291 19.0126 2.5126L13.1499 8.3752L11.5 12.5Z");
}

</style>
