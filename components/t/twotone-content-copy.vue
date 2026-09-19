<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxyjxbnqt"/><path class="wua95abon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-content-copy" /></template>
<style>
.jxyjxbnqt {
  fill: currentColor;
  d: path("M8 7h11v14H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wua95abon {
  fill: currentColor;
  d: path("M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12zm3 4H8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m0 16H8V7h11z");
}

</style>
