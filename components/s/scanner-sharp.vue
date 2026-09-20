<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7_kqccjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scanner-sharp" /></template>
<style>
.w7_kqccjk {
  fill: currentColor;
  d: path("M17.6 12L3.5 6.9L4.2 5L21 11.15V20H3v-8zM10 17h8v-2h-8zm-4 0h2v-2H6z");
}

</style>
