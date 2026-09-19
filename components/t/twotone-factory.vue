<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qejjnkbkg"/><path class="gjusu2b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-factory" /></template>
<style>
.gjusu2b1w {
  fill: currentColor;
  d: path("M22 22H2V10l7-3v2l5-2v3h3l1-8h3l1 8zM12 9.95l-5 2V10l-3 1.32V20h16v-8h-8zM11 18h2v-4h-2zm-4 0h2v-4H7zm10-4h-2v4h2z");
}

.qejjnkbkg {
  fill: currentColor;
  d: path("M12 12V9.95l-5 2V10l-3 1.32V20h16v-8zm-3 6H7v-4h2zm4 0h-2v-4h2zm4 0h-2v-4h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
