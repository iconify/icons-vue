<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqkg3b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-perm-scan-wifi" /></template>
<style>
.xoqkg3b8b {
  fill: currentColor;
  d: path("M12 3C6.95 3 3.15 4.85 0 7.23L12 22L24 7.25C20.85 4.87 17.05 3 12 3m1 13h-2v-6h2zm-2-8V6h2v2z");
}

</style>
