<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysodpccqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-no-sim" /></template>
<style>
.ysodpccqb {
  fill: currentColor;
  d: path("M21.26 21.21L3.79 3.74L2.38 5.15l2.74 2.74l-.12.12V19c0 1.1.9 2 2 2h10c.35 0 .68-.1.97-.26l1.88 1.88zM7 19V9.77L16.23 19zm3.84-14H17v9.11l2 2V5c0-1.1-.9-2-2-2h-6.99L7.95 5.06l1.41 1.41z");
}

</style>
