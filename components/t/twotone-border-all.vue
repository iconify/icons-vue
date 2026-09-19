<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o82tddbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-border-all" /></template>
<style>
.o82tddbwb {
  fill: currentColor;
  d: path("M21 3H3v18h18zM11 19H5v-6h6zm0-8H5V5h6zm8 8h-6v-6h6zm0-8h-6V5h6z");
}

</style>
