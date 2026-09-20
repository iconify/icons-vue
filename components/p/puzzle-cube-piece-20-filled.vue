<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="st37kbc6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-cube-piece-20-filled" /></template>
<style>
.st37kbc6s {
  fill: currentColor;
  d: path("M7 17H6a3 3 0 0 1-3-3v-1h4zm4 0H8v-4h3zm5-3a3 3 0 0 1-3 3h-1v-4h4zm-9-2H3V9h4zm4 0H8V9h3zm5 0h-4V9h4zM7 8H3V7a3 3 0 0 1 3-3h1zm4 0H8V4h3zm4.371-6.526a1 1 0 0 1 1.338.069l1.752 1.752a1 1 0 0 1 0 1.414l-1.752 1.752a1 1 0 0 1-1.338.07l-.076-.07l-1.752-1.752a1 1 0 0 1 0-1.414l1.752-1.752z");
}

</style>
