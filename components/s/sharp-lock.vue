<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auyf8vbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-lock" /></template>
<style>
.auyf8vbjn {
  fill: currentColor;
  d: path("M20 8h-3V6.21c0-2.61-1.91-4.94-4.51-5.19A5.01 5.01 0 0 0 7 6v2H4v14h16zm-8 9c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2M9 8V6c0-1.66 1.34-3 3-3s3 1.34 3 3v2z");
}

</style>
