<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofbok1bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-1-20-filled" /></template>
<style>
.ofbok1bim {
  fill: currentColor;
  d: path("M10.147 2.022A.5.5 0 0 0 9.5 2.5v9.905a3.25 3.25 0 1 0 .995 2.165l.005-.07V7.177l5.853 1.8A.5.5 0 0 0 17 8.5V5.977a2.5 2.5 0 0 0-1.765-2.39z");
}

</style>
