<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3us7igxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-check" /></template>
<style>
.t3us7igxz {
  fill: currentColor;
  d: path("M9 16.17L4.83 12l-1.42 1.41L9 19L21 7l-1.41-1.41z");
}

</style>
