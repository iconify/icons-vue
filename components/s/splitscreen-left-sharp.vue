<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxq4918bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-left-sharp" /></template>
<style>
.xxq4918bf {
  fill: currentColor;
  d: path("M3 21V3h8v18zm10 0V3h8v18zm6-16h-4v14h4z");
}

</style>
