<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpw5bgexe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-fill-sharp" /></template>
<style>
.vpw5bgexe {
  fill: currentColor;
  d: path("M5.414 8H21a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H11a1 1 0 0 1 0-2h9v-8H5.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
