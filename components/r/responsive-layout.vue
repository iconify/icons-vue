<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1yjc8buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:responsive-layout" /></template>
<style>
.w1yjc8buj {
  fill: currentColor;
  d: path("M16 21V8H9.5V3H21v18zm-6.5 0V10H14v11zM3 21V10h4.5v11z");
}

</style>
