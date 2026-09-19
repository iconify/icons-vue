<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gfi_5ib1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zapya-go" /></template>
<style>
.gfi_5ib1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.66 16.285a54.15 54.15 0 0 1 23.777-4.784s-6.814 9.762-7.54 15.32c0 0 13.822-2.368 21.603 0l-.677 2.561s-17.446-.628-29.817 7.153c-.725-6.476 3.044-17.35 3.044-17.35a49.4 49.4 0 0 0-11.55 1.45Z");
}

</style>
