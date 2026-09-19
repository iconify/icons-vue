<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arpgl49yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-call-missed" /></template>
<style>
.arpgl49yd {
  fill: currentColor;
  d: path("m5 10.41l7 7l9-9L19.59 7L12 14.59L6.41 9H11V7H3v8h2z");
}

</style>
