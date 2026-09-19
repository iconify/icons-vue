<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1b4s2bop"/><path class="qlud_qoet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-app-shortcut" /></template>
<style>
.h1b4s2bop {
  fill: currentColor;
  d: path("M17 18H7V6h10v1h2V3c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-4h-2zm3.38-8.38l.4.87c.09.2.37.2.46 0l.4-.87l.87-.4c.2-.09.2-.37 0-.46l-.87-.4l-.4-.87c-.09-.2-.37-.2-.46 0l-.4.87l-.87.4c-.2.09-.2.37 0 .46z");
}

.qlud_qoet {
  fill: currentColor;
  d: path("m15.54 9l-.79 1.75l-1.75.79a.5.5 0 0 0 0 .91l1.75.79l.79 1.76a.5.5 0 0 0 .91 0l.79-1.75l1.76-.79a.5.5 0 0 0 0-.91l-1.75-.79L16.46 9a.508.508 0 0 0-.92 0m5.23 4.5l-.4.87l-.87.4c-.2.09-.2.37 0 .46l.87.4l.4.87c.09.2.37.2.46 0l.4-.87l.87-.4c.2-.09.2-.37 0-.46l-.87-.4l-.4-.87a.257.257 0 0 0-.46 0");
}

</style>
