<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqtw25ecp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shifts-availability-24-filled" /></template>
<style>
.yqtw25ecp {
  fill: currentColor;
  d: path("M8.5 2a6.5 6.5 0 0 0-.482 12.982a7.5 7.5 0 0 1 6.964-6.964A6.5 6.5 0 0 0 8.5 2m2.78 5.78l-3 3a.75.75 0 0 1-1.06 0l-1.5-1.502a.75.75 0 0 1 1.061-1.06l.97.971l2.469-2.47a.75.75 0 0 1 1.06 1.061M9 15.5a6.5 6.5 0 1 1 13 0a6.5 6.5 0 0 1-13 0m4.217-2.26a.75.75 0 0 0 .005 1.06l1.215 1.203l-1.217 1.217a.75.75 0 1 0 1.06 1.06l1.22-1.219l1.215 1.219a.75.75 0 0 0 1.062-1.06l-1.215-1.217l1.212-1.204a.75.75 0 0 0-1.057-1.064L15.5 14.444l-1.221-1.21a.75.75 0 0 0-1.06.005");
}

</style>
