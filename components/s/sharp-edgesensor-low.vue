<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp9x9evsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-edgesensor-low" /></template>
<style>
.zp9x9evsj {
  fill: currentColor;
  d: path("M2 7h2v7H2zm18 3h2v7h-2zM6 2v20h12V2zm10 15H8V7h8z");
}

</style>
