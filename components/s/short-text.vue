<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxt89abcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:short-text" /></template>
<style>
.oxt89abcn {
  fill: currentColor;
  d: path("M4 15v-2h10v2zm0-4V9h16v2z");
}

</style>
