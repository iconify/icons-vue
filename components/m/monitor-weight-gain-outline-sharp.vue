<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0g1efb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitor-weight-gain-outline-sharp" /></template>
<style>
.t0g1efb8u {
  fill: currentColor;
  d: path("M18 23v-3h-3v-2h3v-3h2v3h3v2h-3v3zM5 19V5zm-2 2V3h18v10h-2V5H5v14h8v2zm11.125-9.875Q15 10.25 15 9t-.875-2.125T12 6t-2.125.875T9 9t.875 2.125T12 12t2.125-.875M10 9.5v-1h1v1zm1.5 0v-1h1v1zm1.5 0v-1h1v1z");
}

</style>
