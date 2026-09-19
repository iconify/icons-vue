<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wio4a_bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pie-chart" /></template>
<style>
.wio4a_bak {
  fill: currentColor;
  d: path("M11 2v20c-5.07-.5-9-4.79-9-10s3.93-9.5 9-10m2.03 0v8.99H22c-.47-4.74-4.24-8.52-8.97-8.99m0 11.01V22c4.74-.47 8.5-4.25 8.97-8.99z");
}

</style>
