<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqhjvcjvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-chop-sharp" /></template>
<style>
.vqhjvcjvu {
  fill: currentColor;
  d: path("M2 20V4h20v16zm4.375-2H20V6h-4.325L18 15z");
}

</style>
