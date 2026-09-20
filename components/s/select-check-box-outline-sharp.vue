<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebzm2gb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:select-check-box-outline-sharp" /></template>
<style>
.ebzm2gb_l {
  fill: currentColor;
  d: path("M3 21V3h16.875l-2 2H5v14h14v-6.65l2-2V21zm8.525-4l-5.65-5.65l1.4-1.4l4.25 4.25L20.7 5.025L22.125 6.4z");
}

</style>
