<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8dm5kbdf"/><path class="ppo1ivb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-comments-disabled" /></template>
<style>
.h8dm5kbdf {
  fill: currentColor;
  d: path("M6.83 4H20v12h-1.17l-2-2H18v-2h-3.17l-1-1H18V9h-6.17l-1-1H18V6H8.83zm6.34 12l-2-2H6v-2h3.17l-1-1H6V9h.17L4 6.83V16z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ppo1ivb-f {
  fill: currentColor;
  d: path("M18.83 16H20V4H6.83l-2-2H20c1.1 0 2 .9 2 2v15.17zM18 6H8.83l2 2H18zm0 3h-6.17l2 2H18zm0 5v-2h-3.17l2 2zm3.9 7.9l-1.41 1.41L15.17 18H4c-1.1 0-2-.9-2-2V4.83L.69 3.51L2.1 2.1zM13.17 16l-2-2H6v-2h3.17l-1-1H6V9h.17L4 6.83V16z");
}

</style>
