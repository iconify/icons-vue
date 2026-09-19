<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn9n5imgx"/><path class="yo78kybaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-wb-iridescent" /></template>
<style>
.vn9n5imgx {
  fill: currentColor;
  d: path("M7 11h10v2H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yo78kybaj {
  fill: currentColor;
  d: path("M5 15h14V9H5zm2-4h10v2H7zm4-10h2v3h-2zm6.25 4.39l1.41 1.41l1.8-1.79l-1.42-1.41zM11 20h2v3h-2zm6.24-1.29l1.79 1.8l1.42-1.42l-1.8-1.79zM5.34 6.805l-1.788-1.79L4.96 3.61l1.788 1.788zM3.55 19.08l1.41 1.42l1.79-1.8l-1.41-1.41z");
}

</style>
