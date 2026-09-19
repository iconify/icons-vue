<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qps7k_i9f"/><path class="dwu8l7bop"/><path class="omilo2bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-chart" /></template>
<style>
.dwu8l7bop {
  fill: currentColor;
  d: path("M19 19H5V5h9V3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-9h-2z");
}

.omilo2bku {
  fill: currentColor;
  d: path("M7 10h2v7H7zm12-5V3h-2v2h-2v2h2v2h2V7h2V5z");
}

.qps7k_i9f {
  fill: currentColor;
  d: path("M11 7h2v10h-2zm4 6h2v4h-2z");
}

</style>
