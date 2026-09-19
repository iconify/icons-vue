<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boaplbcvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-house-siding" /></template>
<style>
.boaplbcvv {
  fill: currentColor;
  d: path("M19 12h1.7c.46 0 .68-.57.33-.87L12.67 3.6c-.38-.34-.96-.34-1.34 0l-8.36 7.53c-.34.3-.13.87.33.87H5v7c0 .55.45 1 1 1s1-.45 1-1v-1h10v1c0 .55.45 1 1 1s1-.45 1-1zM7.21 10h9.58l.21.19V12H7v-1.81zm7.36-2H9.43L12 5.69zM7 16v-2h10v2z");
}

</style>
