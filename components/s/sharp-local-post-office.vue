<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyip1_bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-post-office" /></template>
<style>
.qyip1_bgz {
  fill: currentColor;
  d: path("M22 4H2.01v16H22zm-2 4l-8 5l-8-5V6l8 5l8-5z");
}

</style>
