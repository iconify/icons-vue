<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idf7tq4oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:martini-fill-sharp" /></template>
<style>
.idf7tq4oo {
  fill: currentColor;
  d: path("M4 2h16a1.002 1.002 0 0 1 .707 1.707L13 11.414V20h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3v-8.586L3.293 3.707A1 1 0 0 1 4 2m13.586 2H6.414l1 1h9.172Z");
}

</style>
