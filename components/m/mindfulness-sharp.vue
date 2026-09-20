<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8rgnjckb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mindfulness-sharp" /></template>
<style>
.k8rgnjckb {
  fill: currentColor;
  d: path("M6 22v-4.3q-1.425-1.3-2.212-3.037T3 11q0-3.75 2.625-6.375T12 2q3.125 0 5.538 1.838t3.137 4.787L22.3 15H19v5h-4v2zm5-8h2V7h-2zm3-1.5h2V8h-2zM8 12h2V8H8z");
}

</style>
