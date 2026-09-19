<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p88ps52_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-subdirectory-arrow-right" /></template>
<style>
.p88ps52_s {
  fill: currentColor;
  d: path("m19 15l-6 6l-1.42-1.42L15.17 16H4V4h2v10h9.17l-3.59-3.58L13 9z");
}

</style>
