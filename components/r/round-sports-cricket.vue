<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yppturbme"/><circle class="rzsmqdd7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-sports-cricket" /></template>
<style>
.rzsmqdd7p {
  cx: 18.5px;
  cy: 5.5px;
  r: 3.5px;
  fill: currentColor;
}

.yppturbme {
  fill: currentColor;
  d: path("M15.05 12.81L6.56 4.32a.996.996 0 0 0-1.41 0L2.32 7.15a.996.996 0 0 0 0 1.41l8.49 8.49c.39.39 1.02.39 1.41 0l2.83-2.83a.996.996 0 0 0 0-1.41m-.71 4.95l3.53 3.53c.39.39 1.03.39 1.42 0s.39-1.03 0-1.42l-3.53-3.53z");
}

</style>
