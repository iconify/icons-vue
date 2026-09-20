<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwu4u_bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-center-sharp" /></template>
<style>
.qwu4u_bcv {
  fill: currentColor;
  d: path("M2 20V4h20v16zm6-5h8V9H8z");
}

</style>
