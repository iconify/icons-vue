<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrey22syf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-indeterminate-check-box" /></template>
<style>
.lrey22syf {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-4 10H7v-2h10z");
}

</style>
