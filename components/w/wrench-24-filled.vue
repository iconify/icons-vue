<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cusofwbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wrench-24-filled" /></template>
<style>
.cusofwbvf {
  fill: currentColor;
  d: path("M16.5 2a5.5 5.5 0 0 0-5.348 6.789L2.841 17.1a2.871 2.871 0 1 0 4.06 4.06l8.313-8.311q.621.15 1.286.151a5.5 5.5 0 0 0 5.218-7.245a.75.75 0 0 0-1.242-.292l-2.444 2.444a.75.75 0 0 1-1.06 0l-.879-.878a.75.75 0 0 1 0-1.06l2.445-2.445a.75.75 0 0 0-.293-1.241A5.5 5.5 0 0 0 16.5 2");
}

</style>
