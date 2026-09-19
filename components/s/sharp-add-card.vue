<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-n-y7b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add-card" /></template>
<style>
.e-n-y7b3q {
  fill: currentColor;
  d: path("M2.01 4L2 20h12v-2H4v-6h18V4zM20 8H4V6h16zm4 9v2h-3v3h-2v-3h-3v-2h3v-3h2v3z");
}

</style>
