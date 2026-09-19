<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm5fxlbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-note-alt" /></template>
<style>
.wm5fxlbsh {
  fill: currentColor;
  d: path("M21 3h-6.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H3v18h18zm-9-.25c.41 0 .75.34.75.75s-.34.75-.75.75s-.75-.34-.75-.75s.34-.75.75-.75M9.1 17H7v-2.14l5.96-5.96l2.12 2.12zm8.1-8.09l-1.41 1.41l-2.13-2.12l1.41-1.41z");
}

</style>
