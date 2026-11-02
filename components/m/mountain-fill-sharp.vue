<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8x7s6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mountain-fill-sharp" /></template>
<style>
.h8x7s6bbu {
  fill: currentColor;
  d: path("M9.106 4.553a.998.998 0 0 1 1.788 0L13 8.764l1.106-2.211a.998.998 0 0 1 1.788 0l6 12A1 1 0 0 1 21 20H3a1 1 0 0 1-.894-1.447Z");
}

</style>
