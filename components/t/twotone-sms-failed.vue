<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="risb1mboy"/><path class="tz6qxzbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sms-failed" /></template>
<style>
.risb1mboy {
  fill: currentColor;
  d: path("M4 17.17L5.17 16H20V4H4zM11 6h2v4h-2zm0 6h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tz6qxzbup {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H5.17L4 17.17V4h16zm-9-4h2v2h-2zm0-6h2v4h-2z");
}

</style>
