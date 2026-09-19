<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zybb7jbrh"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:two-thirty" /></template>
<style>
.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

.zybb7jbrh {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m2 33.445V58h-4V35.445a4 4 0 0 1-.944-.758l-3.029.813L25 31.666l3.201-.859A3.98 3.98 0 0 1 30 28.555V26h4v2.555c.251.146.484.313.697.509L47.975 25.5L49 29.336L35.905 32.85A4 4 0 0 1 34 35.445");
}

</style>
