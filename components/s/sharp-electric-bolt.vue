<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybqasgb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-electric-bolt" /></template>
<style>
.ybqasgb2p {
  fill: currentColor;
  d: path("M15 2L2.5 13L13 14l-5 7l1 1l12.5-11L11 10l5-7z");
}

</style>
