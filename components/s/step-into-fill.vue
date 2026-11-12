<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x52dtme1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-into-fill" /></template>
<style>
.x52dtme1z {
  fill: currentColor;
  d: path("M13 3v7.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 10.586V3a1 1 0 0 1 2 0M9 19a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
