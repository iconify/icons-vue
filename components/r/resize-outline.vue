<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3yn2rbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:resize-outline" /></template>
<style>
.c3yn2rbff {
  fill: currentColor;
  d: path("M19 9V5h-4V3h6v6zM3 21v-6h2v4h4v2zm0-8v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 0V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm4 0v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2z");
}

</style>
