<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-vnskblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-emergency" /></template>
<style>
.c-vnskblu {
  fill: currentColor;
  d: path("m20.79 9.23l-2-3.46L14 8.54V3h-4v5.54L5.21 5.77l-2 3.46L8 12l-4.79 2.77l2 3.46L10 15.46V21h4v-5.54l4.79 2.77l2-3.46L16 12z");
}

</style>
