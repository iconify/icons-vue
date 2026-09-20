<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm1a_jb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:roofing-outline-sharp" /></template>
<style>
.vm1a_jb5k {
  fill: currentColor;
  d: path("M9 20v-6h6v6zm2-2h2v-2h-2zm-8.8-5L1 11.4L12 3l4 3.05V4h3v4.35l4 3.05l-1.2 1.6L12 5.525zm9.8 4");
}

</style>
