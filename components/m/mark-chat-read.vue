<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvsm75ysx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-chat-read" /></template>
<style>
.yvsm75ysx {
  fill: currentColor;
  d: path("m17.35 20l-3.525-3.55l1.4-1.4l2.125 2.125l4.25-4.25L23 14.35zM2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v7H12v7H6z");
}

</style>
