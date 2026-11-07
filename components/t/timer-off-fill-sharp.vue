<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr7om0j3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:timer-off-fill-sharp" /></template>
<style>
.rr7om0j3g {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414l-2.643-2.642A9 9 0 1 1 5.935 6.35L2.293 2.707a.999.999 0 1 1 1.414-1.414m15.257 12.428L9.573 4.33A9 9 0 0 1 11 4.054V4h-1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2h-1v.054a9 9 0 0 1 4.618 1.913l1.675-1.674a.999.999 0 1 1 1.414 1.414l-1.674 1.675a9 9 0 0 1 1.637 8.045Z");
}

</style>
