<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_vk2bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-horizontal-fill" /></template>
<style>
.ox_vk2bqq {
  fill: currentColor;
  d: path("M4.158 11.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
