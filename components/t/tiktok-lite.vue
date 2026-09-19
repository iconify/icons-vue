<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zafmmq91j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiktok-lite" /></template>
<style>
.zafmmq91j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.735 22.4c-5.827-.005-10.554 4.714-10.56 10.54c-.006 5.827 4.713 10.555 10.54 10.56c5.811.005 10.532-4.69 10.56-10.5V4.5c0 5.827 4.723 10.55 10.55 10.55M12.464 4.607l-.893 4.28h2.467l-3.84 6.65l.894-4.28H8.625z");
}

</style>
