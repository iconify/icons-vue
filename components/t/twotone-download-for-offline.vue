<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="advw2ekol"/><path class="mr3u7xbpx"/><path class="bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-download-for-offline" /></template>
<style>
.advw2ekol {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8m-1 6V6h2v4h3l-4 4l-4-4zm6 7H7v-2h10z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.bwibdw4bb {
  fill: currentColor;
  d: path("M12 2C6.49 2 2 6.49 2 12s4.49 10 10 10s10-4.49 10-10S17.51 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8");
}

.mr3u7xbpx {
  fill: currentColor;
  d: path("M16 10h-3V6h-2v4H8l4 4zm-9 5h10v2H7z");
}

</style>
