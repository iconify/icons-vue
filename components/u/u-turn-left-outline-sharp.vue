<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhx5q-eni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:u-turn-left-outline-sharp" /></template>
<style>
.mhx5q-eni {
  fill: currentColor;
  d: path("M16 21V9q0-1.65-1.175-2.825T12 5T9.175 6.175T8 9v4.2l1.6-1.6L11 13l-4 4l-4-4l1.4-1.4L6 13.2V9q0-2.5 1.75-4.25T12 3t4.25 1.75T18 9v12z");
}

</style>
