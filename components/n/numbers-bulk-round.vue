<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u567ceb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:numbers-bulk-round" /></template>
<style>
.u567ceb2m {
  fill: currentColor;
  d: path("M4.293 6.293A1 1 0 0 1 6 7v10a1 1 0 0 1-2 0V9.414l-.293.293a.999.999 0 1 1-1.414-1.414ZM11 6a3 3 0 0 1 3 3v1a2.997 2.997 0 0 1-3 3a.997.997 0 0 0-1 1v1a.997.997 0 0 0 1 1h2a1 1 0 0 1 0 2h-2a3 3 0 0 1-3-3v-1a2.997 2.997 0 0 1 3-3a.997.997 0 0 0 1-1V9a.997.997 0 0 0-1-1H9a1 1 0 0 1 0-2Zm8 0a3 3 0 0 1 3 3v1c0 .74-.27 1.45-.764 2c.493.551.765 1.26.764 2v1a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2Z");
}

</style>
