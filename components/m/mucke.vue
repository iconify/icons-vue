<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g61xclbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mucke" /></template>
<style>
.g61xclbgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.1 6.6h-5.6l-4.8 3.5V6.6h-10l-4.9 3.7V6.6H5.5v34.8l7.3-7.1V14h7.5v27.4l7.4-7.7V14h7.4v27l7.4-7.7V6.6z");
}

</style>
