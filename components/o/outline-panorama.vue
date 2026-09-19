<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r93eryfmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-panorama" /></template>
<style>
.r93eryfmu {
  fill: currentColor;
  d: path("M21 4H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H3V6h18zm-6.5-7L11 15.51L8.5 12.5L5 17h14z");
}

</style>
