<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvwte-bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:memory-alt-sharp" /></template>
<style>
.rvwte-bzr {
  fill: currentColor;
  d: path("M6.5 14.5h1v-5h-1zm5 0h1v-5h-1zm5 0h1v-5h-1zM5.5 20v-2H3V6h2.5V4h1v2h5V4h1v2h5V4h1v2H21v12h-2.5v2h-1v-2h-5v2h-1v-2h-5v2z");
}

</style>
