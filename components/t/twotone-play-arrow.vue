<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-0w78vs"/><path class="r2v6go4yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-play-arrow" /></template>
<style>
.ha-0w78vs {
  fill: currentColor;
  d: path("M10 8.64v6.72L15.27 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r2v6go4yc {
  fill: currentColor;
  d: path("m8 19l11-7L8 5zm2-10.36L15.27 12L10 15.36z");
}

</style>
