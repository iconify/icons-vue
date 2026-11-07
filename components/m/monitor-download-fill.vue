<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzkhpvbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-fill" /></template>
<style>
.xzkhpvbqp {
  fill: currentColor;
  d: path("M6 3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m5.293 11.707a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 11.586V7a1 1 0 0 0-2 0v4.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
