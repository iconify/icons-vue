<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqkagcber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shift-lock-outline" /></template>
<style>
.xqkagcber {
  fill: currentColor;
  d: path("M8 18v-5H3l9-11l9 11h-5v5zm2-2h4v-5h2.775L12 5.15L7.225 11H10zm-6 6v-2h16v2z");
}

</style>
