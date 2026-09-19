<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewqsqbb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-check-box-outline-blank" /></template>
<style>
.ewqsqbb3w {
  fill: currentColor;
  d: path("M19 5v14H5V5zm2-2H3v18h18z");
}

</style>
