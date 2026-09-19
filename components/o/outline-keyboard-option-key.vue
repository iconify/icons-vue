<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhh-k1b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-keyboard-option-key" /></template>
<style>
.zhh-k1b_k {
  fill: currentColor;
  d: path("M15 5h6v2h-6zM9 5H3v2h4.85l6.92 12H21v-2h-5.07z");
}

</style>
