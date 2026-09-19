<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy25swa3k"/><path class="zie785cpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-gpp-maybe" /></template>
<style>
.jy25swa3k {
  fill: currentColor;
  d: path("M6 6.39v4.7c0 4 2.55 7.7 6 8.83c3.45-1.13 6-4.82 6-8.83v-4.7l-6-2.25zM13 16h-2v-2h2zm0-4h-2V7h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zie785cpj {
  fill: currentColor;
  d: path("M12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm6 9.09c0 4-2.55 7.7-6 8.83c-3.45-1.13-6-4.82-6-8.83v-4.7l6-2.25l6 2.25zM11 16h2v-2h-2zm0-4h2V7h-2z");
}

</style>
