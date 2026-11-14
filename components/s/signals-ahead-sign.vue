<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w040w824h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:signals-ahead-sign" /></template>
<style>
.w040w824h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.005 3.945l5.05 5.05Q21.3 10.239 21.3 12t-1.245 3.005l-5.05 5.05Q13.761 21.3 12 21.3t-3.005-1.245l-5.05-5.05Q2.7 13.761 2.7 12t1.245-3.005l5.05-5.05Q10.239 2.7 12 2.7t3.005 1.245M15 8.5q0-3-3-3t-3 3v7q0 3 3 3t3-3z");
}

</style>
