<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt79eobkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-polymer" /></template>
<style>
.rt79eobkw {
  fill: currentColor;
  d: path("M19 4h-4L7.11 16.63L4.5 12L9 4H5L.5 12L5 20h4l7.89-12.63L19.5 12L15 20h4l4.5-8z");
}

</style>
