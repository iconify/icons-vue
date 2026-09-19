<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5m944ibi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-north" /></template>
<style>
.h5m944ibi {
  fill: currentColor;
  d: path("M5.71 9.7c.39.39 1.02.39 1.41 0L11 5.83V21c0 .55.45 1 1 1s1-.45 1-1V5.83l3.88 3.88a.996.996 0 1 0 1.41-1.41L12.7 2.7a.996.996 0 0 0-1.41 0L5.71 8.29a.996.996 0 0 0 0 1.41");
}

</style>
