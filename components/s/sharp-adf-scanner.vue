<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcqnl41jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-adf-scanner" /></template>
<style>
.fcqnl41jf {
  fill: currentColor;
  d: path("M22 12h-4V4H6v8H2v8h20zm-6 0H8V6h8zm2 5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
