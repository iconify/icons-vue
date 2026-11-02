<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npl6ucx8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-terminal-fill-sharp" /></template>
<style>
.npl6ucx8q {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-1h16V9H4Zm3.707-7.707l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L7.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414M13 15h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
