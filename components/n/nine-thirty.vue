<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a8fr4tg4i"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:nine-thirty" /></template>
<style>
.a8fr4tg4i {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m5.975 33.5l-3.029-.813c-.273.3-.592.553-.945.758V58h-4V35.445a4 4 0 0 1-1.905-2.597L15 29.334l1.027-3.834l13.276 3.563q.319-.29.696-.508V26h4v2.554a3.97 3.97 0 0 1 1.798 2.251l3.203.859z");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
