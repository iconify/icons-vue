<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2w_eimj"/><path class="fgadp_2sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-low-outline" /></template>
<style>
.fgadp_2sf {
  fill: currentColor;
  d: path("M7.5 15.25C7.91421 15.25 8.25 15.5858 8.25 16V20C8.25 20.4142 7.91421 20.75 7.5 20.75C7.08579 20.75 6.75 20.4142 6.75 20V16C6.75 15.5858 7.08579 15.25 7.5 15.25Z");
}

.hl2w_eimj {
  fill: currentColor;
  d: path("M3 19.25C3.41421 19.25 3.75 19.5858 3.75 20C3.75 20.4142 3.41421 20.75 3 20.75C2.58579 20.75 2.25 20.4142 2.25 20C2.25 19.5858 2.58579 19.25 3 19.25Z");
}

</style>
