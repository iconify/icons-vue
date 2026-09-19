<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsaui--rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-desk" /></template>
<style>
.qsaui--rh {
  fill: currentColor;
  d: path("M2 6v12h2V8h10v10h2v-2h4v2h2V6zm18 2v2h-4V8zm-4 6v-2h4v2z");
}

</style>
