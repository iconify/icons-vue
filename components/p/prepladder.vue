<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ac7l9cc7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prepladder" /></template>
<style>
.ac7l9cc7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 4.5h-10m10 5.571h-10m10 5.572h-10m10 5.571h-10m10 5.572h-10m29-16.715h-10m10 5.572h-10m10 5.571h-10m5 5.572h-10m-4 5.571h-10m10 5.572h-10m10 5.571h-10m24-39h-10");
}

</style>
