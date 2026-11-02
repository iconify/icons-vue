<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idr8lu39n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paperclip-horizontal-bulk" /></template>
<style>
.idr8lu39n {
  fill: currentColor;
  d: path("M15 5a7 7 0 1 1 0 14H7A5 5 0 0 1 7 9h8a3 3 0 1 1 0 6H8a1 1 0 0 1 0-2h7a1 1 0 0 0 0-2H7a3 3 0 1 0 0 6h8a5 5 0 0 0 0-10H7a1 1 0 0 1 0-2Z");
}

</style>
