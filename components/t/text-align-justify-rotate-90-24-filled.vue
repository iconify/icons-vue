<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_m0wkp7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-rotate-90-24-filled" /></template>
<style>
.u_m0wkp7y {
  fill: currentColor;
  d: path("M18 2a1 1 0 0 1 1 1v18a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1M6 2a1 1 0 0 1 1 1v18a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1m7 1a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0z");
}

</style>
