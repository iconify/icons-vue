<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trlv3vb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-border-style" /></template>
<style>
.trlv3vb8h {
  fill: currentColor;
  d: path("M15 21h2v-2h-2zm4 0h2v-2h-2zM7 21h2v-2H7zm4 0h2v-2h-2zm8-4h2v-2h-2zm0-4h2v-2h-2zM3 3v18h2V5h16V3zm16 6h2V7h-2z");
}

</style>
