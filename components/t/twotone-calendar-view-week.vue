<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slkd6edsf"/><path class="tpqf3bizv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-calendar-view-week" /></template>
<style>
.slkd6edsf {
  fill: currentColor;
  d: path("M8.5 6H11v12H8.5zM13 6h2.5v12H13zM4 6h2.5v12H4zm13.5 0H20v12h-2.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tpqf3bizv {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M6.5 18H4V6h2.5zm4.5 0H8.5V6H11zm4.5 0H13V6h2.5zm4.5 0h-2.5V6H20z");
}

</style>
