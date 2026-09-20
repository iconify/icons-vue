<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldeak6hjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-quilt-outline-sharp" /></template>
<style>
.ldeak6hjb {
  fill: currentColor;
  d: path("M3 19V5h18v14zm7.325-8H19V7h-8.675zm5.35 6H19v-4h-3.325zm-5.35 0h3.35v-4h-3.35zM5 17h3.325V7H5z");
}

</style>
