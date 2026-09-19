<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0sxebcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-upload" /></template>
<style>
.aq0sxebcq {
  fill: currentColor;
  d: path("M9 16h6v-6h4l-7-7l-7 7h4zm3-10.17L14.17 8H13v6h-2V8H9.83zM5 18h14v2H5z");
}

</style>
