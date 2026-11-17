<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu_juz8mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-fill" /></template>
<style>
.qu_juz8mp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2C20.105 2 21 2.895 21 4V20H22C22.552 20 23 20.448 23 21C23 21.552 22.552 22 22 22H2C1.448 22 1 21.552 1 21C1 20.448 1.448 20 2 20H3V4C3 2.895 3.895 2 5 2H19ZM5 8V10H11V14H5V16H11V20H13V16H19V14H13V10H19V8H5Z");
}

</style>
