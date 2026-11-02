<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqyjq5bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-fill-sharp" /></template>
<style>
.wqyjq5bca {
  fill: currentColor;
  d: path("M10 6h4V3a1 1 0 0 1 2 0v3h2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-5v3a1 1 0 0 1-2 0v-3H6a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h2V3a1 1 0 0 1 2 0Z");
}

</style>
