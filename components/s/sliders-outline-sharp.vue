<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yit-lcg9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sliders-outline-sharp" /></template>
<style>
.yit-lcg9h {
  fill: currentColor;
  d: path("M2 15V9h20v6zm12-2h6v-2h-6z");
}

</style>
