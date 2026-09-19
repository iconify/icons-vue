<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osv1_dqxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-candlestick-chart" /></template>
<style>
.osv1_dqxe {
  fill: currentColor;
  d: path("M9 4H7v2H5v12h2v2h2v-2h2V6H9zm0 12H7V8h2zm10-8h-2V4h-2v4h-2v7h2v5h2v-5h2zm-2 5h-2v-3h2z");
}

</style>
