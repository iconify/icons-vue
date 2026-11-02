<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kygr6obhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-fill" /></template>
<style>
.kygr6obhh {
  fill: currentColor;
  d: path("M21.591 16.488A2.999 2.999 0 0 1 19 21H5a2.999 2.999 0 0 1-2.591-4.512l7-12a3 3 0 0 1 5.182 0Z");
}

</style>
