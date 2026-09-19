<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4eflbb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-signal-wifi-connected-no-internet-4" /></template>
<style>
.z4eflbb3y {
  fill: currentColor;
  d: path("M24 8.98A16.88 16.88 0 0 0 12 4C7.31 4 3.07 5.9 0 8.98L12 21v-9h8.99zM19.59 14l-2.09 2.09l-.3-.3L15.41 14L14 15.41l1.79 1.79l.3.3L14 19.59L15.41 21l2.09-2.08L19.59 21L21 19.59l-2.08-2.09L21 15.41z");
}

</style>
