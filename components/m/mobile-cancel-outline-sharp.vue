<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx5wxabid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-cancel-outline-sharp" /></template>
<style>
.qx5wxabid {
  fill: currentColor;
  d: path("M9.65 15.75L12 13.4l2.35 2.35l1.4-1.4L13.4 12l2.35-2.35l-1.4-1.4L12 10.6L9.65 8.25l-1.4 1.4L10.6 12l-2.35 2.35zM5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>
