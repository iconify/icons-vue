<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otruaepyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-dehaze" /></template>
<style>
.otruaepyy {
  fill: currentColor;
  d: path("M2 16v2h20v-2zm0-5v2h20v-2zm0-5v2h20V6z");
}

</style>
