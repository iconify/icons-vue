<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxuqhib4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-agenda-sharp" /></template>
<style>
.qxuqhib4c {
  fill: currentColor;
  d: path("M4 19.385v-6h16v6zm0-8.77v-6h16v6z");
}

</style>
