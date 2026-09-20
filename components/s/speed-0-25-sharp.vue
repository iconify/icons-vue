<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv13hjb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-25-sharp" /></template>
<style>
.wv13hjb3x {
  fill: currentColor;
  d: path("M4 17v-2h2v2zm10 0v-2h4v-2h-4V7h6v2h-4v2h4v6zm-7 0v-6h4V9H7V7h6v6H9v2h4v2z");
}

</style>
