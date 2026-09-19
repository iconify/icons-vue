<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltufvmsdc"/><path class="kpizqibwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-app-shortcut" /></template>
<style>
.kpizqibwl {
  fill: currentColor;
  d: path("m16 8l-1.25 2.75L12 12l2.75 1.25L16 16l1.25-2.75L20 12l-2.75-1.25zm5 5l-.62 1.38L19 15l1.38.62L21 17l.62-1.38L23 15l-1.38-.62z");
}

.ltufvmsdc {
  fill: currentColor;
  d: path("M17 18H7V6h10v1h2V1H5v22h14v-6h-2zm3.38-8.38L21 11l.62-1.38L23 9l-1.38-.62L21 7l-.62 1.38L19 9z");
}

</style>
