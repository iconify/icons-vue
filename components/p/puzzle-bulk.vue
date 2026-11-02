<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icg-4ullf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle-bulk" /></template>
<style>
.icg-4ullf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.237 6H19a3 3 0 0 1 3 3v3a1 1 0 0 1-1.447.894A1.237 1.237 0 0 0 18.764 14a1.232 1.232 0 0 0 1.789 1.106A1 1 0 0 1 22 16v3a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-1.763a3.238 3.238 0 0 1 0-6.474V9a3 3 0 0 1 3-3h1.763a3.238 3.238 0 0 1 6.474 0");
}

</style>
