<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt3wtssut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mars-fill-sharp" /></template>
<style>
.mt3wtssut {
  fill: currentColor;
  d: path("M11.477 11.109L18.586 4H15a1 1 0 0 1 0-2h6a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0V5.414l-7.109 7.109a6 6 0 1 1-1.414-1.414");
}

</style>
