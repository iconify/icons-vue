<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9p70t9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:queue-play-next-outline-sharp" /></template>
<style>
.nv9p70t9q {
  fill: currentColor;
  d: path("M19.5 22.5L18 21l3-3l-3-3l1.5-1.5L24 18zM8 21v-2H2V3h20v9h-2V5H4v12h13v2h-2v2zm3-6h2v-3h3v-2h-3V7h-2v3H8v2h3zm-7 2V5z");
}

</style>
