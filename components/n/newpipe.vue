<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="witobzg0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:newpipe" /></template>
<style>
.witobzg0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.1 4.5L40.9 24L17.64 37.42v-7L28.76 24l-15.6-9v25L7.1 43.5Z");
}

</style>
