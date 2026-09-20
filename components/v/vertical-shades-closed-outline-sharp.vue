<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaf19rb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-shades-closed-outline-sharp" /></template>
<style>
.jaf19rb3s {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm4-2h1.5V5H6zm3.5 0H11V5H9.5zm3.5 0h1.5V5H13zm3.5 0H18V5h-1.5z");
}

</style>
