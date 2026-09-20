<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwgrgb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:south-west-sharp" /></template>
<style>
.sxwgrgb_u {
  fill: currentColor;
  d: path("M5 19V9h2v6.6L18.6 4L20 5.4L8.4 17H15v2z");
}

</style>
