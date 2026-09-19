<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbcn9dbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-expand-more" /></template>
<style>
.jbcn9dbsl {
  fill: currentColor;
  d: path("M16.59 8.59L12 13.17L7.41 8.59L6 10l6 6l6-6z");
}

</style>
