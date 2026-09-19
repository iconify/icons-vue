<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nysjy7oac"/><path class="ko-qp_e8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-turned-in" /></template>
<style>
.ko-qp_e8c {
  fill: currentColor;
  d: path("m7 17.97l4.21-1.81l.79-.34l.79.34L17 17.97V5H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nysjy7oac {
  fill: currentColor;
  d: path("M17 3H7c-1.1 0-1.99.9-1.99 2L5 21l7-3l7 3V5c0-1.1-.9-2-2-2m0 14.97l-4.21-1.81l-.79-.34l-.79.34L7 17.97V5h10z");
}

</style>
