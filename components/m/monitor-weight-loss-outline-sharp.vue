<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1muqtbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitor-weight-loss-outline-sharp" /></template>
<style>
.k1muqtbdi {
  fill: currentColor;
  d: path("M15 18h8v2h-8zM5 19V5zm-2 2V3h18v10h-2V5H5v14h8v2zm11.125-9.875Q15 10.25 15 9t-.875-2.125T12 6t-2.125.875T9 9t.875 2.125T12 12t2.125-.875M10 9.5v-1h1v1zm1.5 0v-1h1v1zm1.5 0v-1h1v1z");
}

</style>
