<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylju5pbyn"/><path class="hc13cabmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-wine-bar" /></template>
<style>
.hc13cabmt {
  fill: currentColor;
  d: path("M6 3v6c0 2.97 2.16 5.43 5 5.91V19H8v2h8v-2h-3v-4.09c2.84-.48 5-2.94 5-5.91V3zm6 10c-1.86 0-3.41-1.28-3.86-3h7.72c-.45 1.72-2 3-3.86 3m4-5H8V5h8z");
}

.ylju5pbyn {
  fill: currentColor;
  d: path("M12 13c-1.86 0-3.41-1.28-3.86-3h7.72c-.45 1.72-2 3-3.86 3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
