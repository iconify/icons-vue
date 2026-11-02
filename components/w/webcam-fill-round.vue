<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zca_fftim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-fill-round" /></template>
<style>
.zca_fftim {
  fill: currentColor;
  d: path("M13 17.939V20h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3v-2.061a8 8 0 0 1-6.984-8.44a8 8 0 0 1 15.968 0A8 8 0 0 1 13 17.939M12 14a4 4 0 1 0 0-8a4 4 0 0 0 0 8m-2-4a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 10");
}

</style>
