<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o-ea71vus"/><circle class="w_ipsacim"/><circle class="ssiuuy_ah"/><path class="iotjdeb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:slightly-frowning-face" /></template>
<style>
.iotjdeb5i {
  fill: currentColor;
  d: path("M32 39.794c-4.539 0-8.082 3.058-9.836 6.491c-.471.918.154 1.913.848 1.34c5.793-4.801 12.219-4.771 17.977 0c.693.573 1.318-.422.848-1.34c-1.755-3.433-5.3-6.491-9.837-6.491");
}

.o-ea71vus {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.164 59.5 32 59.5");
}

.ssiuuy_ah {
  cx: 43.5px;
  cy: 26.592px;
  r: 5px;
  fill: currentColor;
}

.w_ipsacim {
  cx: 20.5px;
  cy: 26.592px;
  r: 5px;
  fill: currentColor;
}

</style>
