<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7_64-7kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:man-3-outline-sharp" /></template>
<style>
.b7_64-7kh {
  fill: currentColor;
  d: path("M10 22.25v-7H8v-8h8v8h-2v7zM12 6.5L9.75 4.25L12 2l2.25 2.25z");
}

</style>
