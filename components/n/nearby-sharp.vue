<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx6_gykrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nearby-sharp" /></template>
<style>
.tx6_gykrb {
  fill: currentColor;
  d: path("M12 15.516L8.485 12L12 8.485L15.516 12zm0 5.49L2.975 11.98L12 2.956l9.025 9.025zm0-1.825l7.2-7.2l-7.18-7.2l-7.2 7.2z");
}

</style>
