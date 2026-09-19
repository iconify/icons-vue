<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x06ohzb0c"/><path class="w4xdj_4_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-phonelink-ring" /></template>
<style>
.w4xdj_4_t {
  fill: currentColor;
  d: path("M14 1H4c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 19H4V4h10zm6.1-12.3l-1 1c1.8 1.8 1.8 4.6 0 6.5l1 1c2.5-2.3 2.5-6.1 0-8.5M17 10.8c.5.7.5 1.6 0 2.3l1 1c1.2-1.2 1.2-3 0-4.3z");
}

.x06ohzb0c {
  fill: currentColor;
  d: path("M4 4h10v16H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
