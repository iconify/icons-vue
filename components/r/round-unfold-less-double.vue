<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr9vzvb9j"/><path class="a9e9jwbsv"/><path class="t-_3xbcdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-unfold-less-double" /></template>
<style>
.a9e9jwbsv {
  fill: currentColor;
  d: path("m14.46.7l-2.47 2.46L9.53.7a.996.996 0 1 0-1.41 1.41l3.17 3.18c.39.39 1.02.39 1.41 0l3.17-3.18A.996.996 0 1 0 14.46.7M9.54 23.3l2.47-2.46l2.46 2.46a.996.996 0 1 0 1.41-1.41l-3.17-3.18a.996.996 0 0 0-1.41 0l-3.17 3.18a.996.996 0 1 0 1.41 1.41");
}

.sr9vzvb9j {
  fill: currentColor;
  d: path("m14.46 5.7l-2.47 2.46L9.53 5.7a.996.996 0 1 0-1.41 1.41l3.17 3.18c.39.39 1.02.39 1.41 0l3.17-3.18a.996.996 0 1 0-1.41-1.41");
}

.t-_3xbcdm {
  fill: currentColor;
  d: path("m9.54 18.29l2.47-2.45l2.46 2.46a.996.996 0 1 0 1.41-1.41l-3.17-3.18a.996.996 0 0 0-1.41 0l-3.17 3.17a.996.996 0 1 0 1.41 1.41");
}

</style>
