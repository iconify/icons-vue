<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b6ld113jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sparss" /></template>
<style>
.b6ld113jo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.77 6.79a6.73 6.73 0 1 1 0 13.45h-6.72v-6.73a6.72 6.72 0 0 1 6.72-6.72m-19.67 0h.33a6.6 6.6 0 0 1 3.2.9A6.72 6.72 0 0 1 23 13.51h-4a6.73 6.73 0 1 1-13.45 0h4a6.72 6.72 0 0 1 3.35-5.82a6.6 6.6 0 0 1 3.2-.9m17.77 18.28a8.08 8.08 0 1 1-8.07 8.07a8.07 8.07 0 0 1 8.07-8.07M14.25 27l4.06 7l4.06 7H6.12l4.07-7z");
}

</style>
