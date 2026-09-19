<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th7-qtbhx"/><path class="dcac64bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-charging-80" /></template>
<style>
.dcac64bsy {
  fill: currentColor;
  d: path("M13 12.5h2L11 20v-5.5H9L11.93 9H7v13h10V9h-4z");
}

.th7-qtbhx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v5h4.93L13 7v2h4z");
}

</style>
