<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y-cjfwbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pivot-20-filled" /></template>
<style>
.y-cjfwbyv {
  fill: currentColor;
  d: path("M16.225 10.082a.5.5 0 0 1 .628.064l2 2a.5.5 0 1 1-.707.707L17 11.708V14a3 3 0 0 1-3 3h-2.293l1.146 1.146a.5.5 0 1 1-.707.707l-2-2a.5.5 0 0 1 0-.707l2-2a.5.5 0 1 1 .707.707L11.708 16H14a2 2 0 0 0 2-2v-2.293l-1.146 1.146a.5.5 0 1 1-.707-.707l2-2zM14 3a3 3 0 0 1 3 3v3.086a1.5 1.5 0 0 0-1.446.25l-.114.103l-6 6A1.5 1.5 0 0 0 9.087 17H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM6 9a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1zm0-4a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1zm4 0a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1z");
}

</style>
