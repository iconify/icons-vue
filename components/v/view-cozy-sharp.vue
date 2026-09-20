<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew9tmov3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-cozy-sharp" /></template>
<style>
.ew9tmov3s {
  fill: currentColor;
  d: path("M3 10.5V3h7.5v7.5zM3 21v-7.5h7.5V21zm10.5-10.5V3H21v7.5zm0 10.5v-7.5H21V21z");
}

</style>
