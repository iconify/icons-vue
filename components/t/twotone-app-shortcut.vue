<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt493fbfh"/><path class="jpfgx6bck"/><path class="kpizqibwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-app-shortcut" /></template>
<style>
.jpfgx6bck {
  fill: currentColor;
  d: path("M17 18H7V6h10v1h2V3c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-4h-2zM7 3h10v1H7zm10 18H7v-1h10zm3.38-11.38L21 11l.62-1.38L23 9l-1.38-.62L21 7l-.62 1.38L19 9z");
}

.kpizqibwl {
  fill: currentColor;
  d: path("m16 8l-1.25 2.75L12 12l2.75 1.25L16 16l1.25-2.75L20 12l-2.75-1.25zm5 5l-.62 1.38L19 15l1.38.62L21 17l.62-1.38L23 15l-1.38-.62z");
}

.xt493fbfh {
  fill: currentColor;
  d: path("M7 20h10v1H7zM7 3h10v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
