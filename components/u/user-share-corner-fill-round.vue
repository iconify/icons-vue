<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwgehhbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-share-corner-fill-round" /></template>
<style>
.rlwgehhbg {
  fill: currentColor;
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m17 11a1 1 0 0 1-2 0v-1.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L17.586 15H16a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1Zm-11-3v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>
