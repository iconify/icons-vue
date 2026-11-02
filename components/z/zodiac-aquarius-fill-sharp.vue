<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0zptdt9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-aquarius-fill-sharp" /></template>
<style>
.a0zptdt9e {
  fill: currentColor;
  d: path("m2.293 9.293l3-3a.997.997 0 0 1 1.414 0L9 8.586l2.293-2.293a.997.997 0 0 1 1.414 0L15 8.586l2.293-2.293a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L18 8.414l-2.293 2.293a1 1 0 0 1-1.414 0L12 8.414l-2.293 2.293a1 1 0 0 1-1.414 0L6 8.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414m0 7l3-3a1 1 0 0 1 1.414 0L9 15.586l2.293-2.293a1 1 0 0 1 1.414 0L15 15.586l2.293-2.293a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L18 15.414l-2.293 2.293a1 1 0 0 1-1.414 0L12 15.414l-2.293 2.293a1 1 0 0 1-1.414 0L6 15.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414");
}

</style>
