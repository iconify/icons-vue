<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qusqzrbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-check-corner-fill" /></template>
<style>
.qusqzrbxj {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m2.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M9 21H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m4.707-4.707l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
