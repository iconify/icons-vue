<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs3w-gm0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-6-fill-round" /></template>
<style>
.zs3w-gm0u {
  fill: currentColor;
  d: path("M9 7v5.999A5 5 0 1 1 7 17V7a5 5 0 0 1 10 0a1 1 0 0 1-2 0a3 3 0 1 0-6 0m0 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
