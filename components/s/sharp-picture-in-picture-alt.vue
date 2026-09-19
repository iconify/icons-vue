<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orql_mwti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-picture-in-picture-alt" /></template>
<style>
.orql_mwti {
  fill: currentColor;
  d: path("M19 11h-8v6h8zm4 10V3H1v18zm-2-1.98H3V4.97h18z");
}

</style>
