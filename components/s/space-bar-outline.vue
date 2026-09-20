<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozy0kubmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:space-bar-outline" /></template>
<style>
.ozy0kubmi {
  fill: currentColor;
  d: path("M4 15V9h2v4h12V9h2v6z");
}

</style>
