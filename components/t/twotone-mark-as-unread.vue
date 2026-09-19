<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpd78hbge"/><path class="a8zlhmb2y"/><path class="d3ciaunii"/><path class="nvz5vg2ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mark-as-unread" /></template>
<style>
.a8zlhmb2y {
  fill: currentColor;
  d: path("M7 12v7h13v-7l-6.5 3.33z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.d3ciaunii {
  fill: currentColor;
  d: path("M16.23 7h2.6c-.06-.47-.36-.94-.79-1.17L10.5 2L2.8 5.83c-.48.26-.8.81-.8 1.34V15c0 1.1.9 2 2 2V7.4L10.5 4z");
}

.kpd78hbge {
  fill: currentColor;
  d: path("M13.5 13.33L20 10H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nvz5vg2ir {
  fill: currentColor;
  d: path("M20 8H7c-1.1 0-2 .9-2 2v9c0 1.1.9 2 2 2h13c1.1 0 2-.9 2-2v-9c0-1.1-.9-2-2-2m0 11H7v-7l6.5 3.33L20 12zm-6.5-5.67L7 10h13z");
}

</style>
