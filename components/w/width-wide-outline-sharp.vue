<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw45hdcdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:width-wide-outline-sharp" /></template>
<style>
.vw45hdcdl {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h2V6H4zm4 0h8V6H8zm10 0h2V6h-2zM8 6v12z");
}

</style>
