<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="rkvc4mvdo"/><path class="awxcszb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-rss-feed" /></template>
<style>
.awxcszb8k {
  fill: currentColor;
  d: path("M4 4.44v2.83c7.03 0 12.73 5.7 12.73 12.73h2.83c0-8.59-6.97-15.56-15.56-15.56m0 5.66v2.83c3.9 0 7.07 3.17 7.07 7.07h2.83c0-5.47-4.43-9.9-9.9-9.9");
}

.rkvc4mvdo {
  cx: 6.18px;
  cy: 17.82px;
  r: 2.18px;
  fill: currentColor;
}

</style>
