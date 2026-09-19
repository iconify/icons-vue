<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo-vwuqjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-directions" /></template>
<style>
.jo-vwuqjn {
  fill: currentColor;
  d: path("M22.41 12L12 1.59L1.59 11.99L12 22.41zM14 14.5V12h-4v3H8v-5h6V7.5l3.5 3.5z");
}

</style>
