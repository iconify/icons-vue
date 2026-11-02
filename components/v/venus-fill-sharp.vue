<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuu6lyu_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:venus-fill-sharp" /></template>
<style>
.tuu6lyu_p {
  fill: currentColor;
  d: path("M13 13.918V16h2a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0v-3H9a1 1 0 0 1 0-2h2v-2.082a6.001 6.001 0 1 1 2 0");
}

</style>
