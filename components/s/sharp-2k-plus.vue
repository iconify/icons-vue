<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5zpgqbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-2k-plus" /></template>
<style>
.m5zpgqbiu {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-11 9.5H7.5v1H10V15H6v-3.5h2.5v-1H6V9h4zm4.25 2.5l-1.75-2.25V15H11V9h1.5v2.25L14.25 9H16l-2.25 3L16 15zM19 12.5h-1.5V14h-1v-1.5H15v-1h1.5V10h1v1.5H19z");
}

</style>
