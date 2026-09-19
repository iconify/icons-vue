<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si07ly1aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-network-ping" /></template>
<style>
.si07ly1aj {
  fill: currentColor;
  d: path("M12 14.67L3.41 6.09L2 7.5l8.5 8.5H4v2h16v-2h-6.5l5.15-5.15A2.5 2.5 0 1 0 19.5 6A2.5 2.5 0 0 0 17 8.5c0 .35.07.67.2.97z");
}

</style>
