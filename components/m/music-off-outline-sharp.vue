<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwkua9_8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-off-outline-sharp" /></template>
<style>
.lwkua9_8c {
  fill: currentColor;
  d: path("M19.339 21.716L2.861 5.238l.707-.707l16.477 16.477zM13.5 11.63l-1-1V4.192h4.885v2.539H13.5zm-3 8.177q-1.246 0-2.123-.877T7.5 16.808t.877-2.124q.877-.876 2.123-.876q.575 0 1.091.204q.517.205.909.615v-1.166l1 1v2.347q0 1.246-.877 2.123t-2.123.877");
}

</style>
