<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="pd6y98bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-dnd-10-filled" /></template>
<style>
.pd6y98bku {
  fill: currentColor;
  d: path("M5 10A5 5 0 1 0 5 0a5 5 0 0 0 0 10M3.5 4.5h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1");
}

</style>
