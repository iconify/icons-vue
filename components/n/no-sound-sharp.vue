<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-jwcftwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:no-sound-sharp" /></template>
<style>
.g-jwcftwu {
  fill: currentColor;
  d: path("M15.4 16L14 14.6l2.6-2.6L14 9.4L15.4 8l2.6 2.6L20.6 8L22 9.4L19.4 12l2.6 2.6l-1.4 1.4l-2.6-2.6zM3 15V9h4l5-5v16l-5-5z");
}

</style>
