<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8rwx5bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-exposure" /></template>
<style>
.m8rwx5bxi {
  fill: currentColor;
  d: path("M21 3H3v18h18zM6 7h5v1.5H6zm13 12H5L19 5zm-4.5-3v2H16v-2h2v-1.5h-2v-2h-1.5v2h-2V16z");
}

</style>
