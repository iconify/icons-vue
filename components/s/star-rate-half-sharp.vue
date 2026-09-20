<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq1l2lbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:star-rate-half-sharp" /></template>
<style>
.tq1l2lbao {
  fill: currentColor;
  d: path("M12 7.9v5.9l2.4 1.85l-.9-3.05l2.25-1.6h-2.8zM5.825 21l2.325-7.6L2 9h7.6L12 1l2.4 8H22l-6.15 4.4l2.325 7.6L12 16.3z");
}

</style>
