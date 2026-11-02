<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv-1fccnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rows-fill-round" /></template>
<style>
.dv-1fccnt {
  fill: currentColor;
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8m0 10h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8");
}

</style>
