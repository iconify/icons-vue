<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzb_m2b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-fill-round" /></template>
<style>
.kzb_m2b_z {
  fill: currentColor;
  d: path("M8.707 3.293L12 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414L14.414 7H17a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5h2.586L7.293 4.707a.999.999 0 1 1 1.414-1.414");
}

</style>
