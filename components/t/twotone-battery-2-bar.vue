<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psl8_7b3y"/><path class="ynju2lalw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-battery-2-bar" /></template>
<style>
.psl8_7b3y {
  fill: currentColor;
  d: path("M9 6h6v10H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ynju2lalw {
  fill: currentColor;
  d: path("M17 5v16c0 .55-.45 1-1 1H8c-.55 0-1-.45-1-1V5c0-.55.45-1 1-1h2V2h4v2h2c.55 0 1 .45 1 1m-2 1H9v10h6z");
}

</style>
