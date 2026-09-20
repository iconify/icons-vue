<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ni2_0bbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:option-thin" /></template>
<style>
.ni2_0bbvx {
  fill: currentColor;
  d: path("M228 192a4 4 0 0 1-4 4h-63.06a11.94 11.94 0 0 1-10.73-6.63L98.63 86.21A4 4 0 0 0 95.06 84H32a4 4 0 0 1 0-8h63.06a11.94 11.94 0 0 1 10.73 6.63l51.58 103.16a4 4 0 0 0 3.57 2.21H224a4 4 0 0 1 4 4M152 84h72a4 4 0 0 0 0-8h-72a4 4 0 0 0 0 8");
}

</style>
