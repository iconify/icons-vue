<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcunkub_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trophy-fill-sharp" /></template>
<style>
.qcunkub_r {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v1h1a3 3 0 1 1 0 6h-1.082A6 6 0 0 1 15 14.198V16c0 .34.232.58.466.793c.142.129.291.25.44.371c.228.186.455.374.669.576c.662.626 1.13 1.358 1.323 2.26H18a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2h.102c.193-.902.661-1.634 1.323-2.26c.214-.202.441-.39.669-.576c.253-.207.527-.412.728-.673A.8.8 0 0 0 9 16v-1.802A6 6 0 0 1 6.082 10H5a3 3 0 1 1 0-6h1ZM5 6a1 1 0 0 0 0 2h1V6Zm14 2a1 1 0 0 0 0-2h-1v2Z");
}

</style>
