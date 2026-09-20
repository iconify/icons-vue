<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzzgxzepm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-left-32-regular" /></template>
<style>
.vzzgxzepm {
  fill: currentColor;
  d: path("M4.68 18.843c-2.24-1.236-2.24-4.457.002-5.693L24.18 2.408C26.346 1.215 29 2.782 29 5.255v21.492c0 2.473-2.654 4.04-4.82 2.846zm.967-3.94a1.25 1.25 0 0 0 0 2.189l19.498 10.75a1.25 1.25 0 0 0 1.854-1.095V5.255a1.25 1.25 0 0 0-1.854-1.095z");
}

</style>
