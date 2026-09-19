<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxxw5db8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-line-style" /></template>
<style>
.xxxw5db8q {
  fill: currentColor;
  d: path("M3 16h5v-2H3zm6.5 0h5v-2h-5zm6.5 0h5v-2h-5zM3 20h2v-2H3zm4 0h2v-2H7zm4 0h2v-2h-2zm4 0h2v-2h-2zm4 0h2v-2h-2zM3 12h8v-2H3zm10 0h8v-2h-8zM3 4v4h18V4z");
}

</style>
