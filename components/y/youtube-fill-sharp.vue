<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju1iq-4lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:youtube-fill-sharp" /></template>
<style>
.ju1iq-4lb {
  fill: currentColor;
  d: path("M7 4h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5m8.514 7.143l-5-3A.997.997 0 0 0 9 9v6a1 1 0 0 0 1.514.857l5-3a.997.997 0 0 0 0-1.714");
}

</style>
