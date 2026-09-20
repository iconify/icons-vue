<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw7ov776y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-flat-head" /></template>
<style>
.sw7ov776y {
  fill: currentColor;
  d: path("M8 21v-2h8v2zm0-3l-1-7l2-8h6l2 8l-1 7zm1.3-8h5.4l-1.25-5h-2.9z");
}

</style>
