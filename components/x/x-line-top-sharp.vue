<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-k3mlf4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:x-line-top-sharp" /></template>
<style>
.p-k3mlf4q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5L18 5M6.7071 8.7071L17.2929 19.2929M17.2929 8.7071L6.7071 19.2929");
}

</style>
