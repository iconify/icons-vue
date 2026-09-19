<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvd5n52gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sports-gymnastics" /></template>
<style>
.mvd5n52gk {
  fill: currentColor;
  d: path("M4 6c0-1.1.9-2 2-2s2 .9 2 2s-.9 2-2 2s-2-.9-2-2M1 9h6l7-5l1.31 1.52l-4.17 2.98H14L21.8 4L23 5.4L14.5 12L14 22h-2l-.5-10L8 11H1z");
}

</style>
