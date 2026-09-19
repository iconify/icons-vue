<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bewe-8bgy"/><path class="bxelbs2jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saturn" /></template>
<style>
.bewe-8bgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.9 13.373a12 12 0 0 0-1.15-.054c-5.056 0-9.35 3.116-10.89 7.446c-.326 1.964 4.626 5.783 5.21 5.42c-.197-5.743 3.019-11.507 6.83-12.812M14.331 25.575c.61 4.99 4.73 8.959 9.94 9.597c-2.005-1.704-3.208-3.82-3.787-6.063");
}

.bxelbs2jc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.346 24.096c5.29 3.884 7.929 7.452 6.955 9.403h0c-1.534 3.076-11.418 1.277-22.078-4.017S3.167 17.403 4.701 14.328c1.133-2.27 6.934-1.94 14.66.837");
}

</style>
