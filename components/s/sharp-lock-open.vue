<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd8gr8q2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-lock-open" /></template>
<style>
.qd8gr8q2w {
  fill: currentColor;
  d: path("M20 8h-3V6.21c0-2.61-1.91-4.94-4.51-5.19A5.01 5.01 0 0 0 7 6h2c0-1.13.6-2.24 1.64-2.7C12.85 2.31 15 3.9 15 6v2H4v14h16zm-2 12H6V10h12zm-6-3c1.1 0 2-.9 2-2s-.9-2-2-2s-2 .9-2 2s.9 2 2 2");
}

</style>
