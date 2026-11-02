<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma3dhobsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subway-fill-round" /></template>
<style>
.ma3dhobsb {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10v9a1 1 0 0 1-2 0v-9a8 8 0 0 0-16 0v9a1 1 0 0 1-2 0Zm4 0a6 6 0 1 1 12 0v5a3 3 0 0 1-2.411 2.942l.305.611a1 1 0 1 1-1.788.894L13.382 20h-2.764l-.724 1.447a1 1 0 1 1-1.788-.894l.305-.611A3 3 0 0 1 6 17Zm8.955-2.696a4 4 0 0 0-5.705-.207l-.001.001A4 4 0 0 0 8.127 11h7.746a4 4 0 0 0-.918-1.696M10.01 14H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
