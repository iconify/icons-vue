<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7k1u5qrq"/><path class="dsw_apn7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-7" /></template>
<style>
.dsw_apn7i {
  fill: currentColor;
  d: path("M3 23h16v-2H3V5H1v16c0 1.1.9 2 2 2m10-8l4-8V5h-6v2h4l-4 8zm8-14H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14z");
}

.v7k1u5qrq {
  fill: currentColor;
  d: path("M7 17h14V3H7zm4-10V5h6v2l-4 8h-2l4-8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
