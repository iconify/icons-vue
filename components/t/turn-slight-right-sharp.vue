<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx6bj0efx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-slight-right-sharp" /></template>
<style>
.wx6bj0efx {
  fill: currentColor;
  d: path("M9 20v-8.4L14.6 6h-2.25V4H18v5.65h-2V7.4l-5 5V20z");
}

</style>
