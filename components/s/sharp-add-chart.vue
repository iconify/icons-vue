<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gicq1ybrs"/><path class="uc7ekibzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add-chart" /></template>
<style>
.gicq1ybrs {
  fill: currentColor;
  d: path("M19 19H5V5h9V3H3v18h18V10h-2z");
}

.uc7ekibzy {
  fill: currentColor;
  d: path("M11 7h2v10h-2zm4 6h2v4h-2zm-8-3h2v7H7zm12-5V3h-2v2h-2v2h2v2h2V7h2V5z");
}

</style>
