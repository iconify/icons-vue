<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crgmwxb_y"/><path class="r0z246bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sram-axs" /></template>
<style>
.crgmwxb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.52 14.56l.02 4.28H29.93L20.88 34.5l-2.64-4.46l9.06-15.58z");
}

.r0z246bsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.76 23.26l-.02 4.48h-5.41L26.69 42.5l-2.62-4.25l8.58-14.91l8.12-.08ZM22.11 5.5l2.55 4.33l-8.96 15.64H7.24l.01-4.32l5.8-.03l9.07-15.63Z");
}

</style>
