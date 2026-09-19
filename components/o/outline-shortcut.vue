<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0luxv5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-shortcut" /></template>
<style>
.aq0luxv5m {
  fill: currentColor;
  d: path("m15 5l-1.41 1.41L15 7.83L17.17 10H8c-2.76 0-5 2.24-5 5v4h2v-4c0-1.65 1.35-3 3-3h9.17L15 14.17l-1.41 1.41L15 17l6-6z");
}

</style>
