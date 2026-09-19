<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s77665bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-edit-note" /></template>
<style>
.s77665bxz {
  fill: currentColor;
  d: path("M3 10h11v2H3zm0-2h11V6H3zm0 8h7v-2H3zm15.01-3.13l.71-.71a.996.996 0 0 1 1.41 0l.71.71c.39.39.39 1.02 0 1.41l-.71.71zm-.71.71l-5.3 5.3V21h2.12l5.3-5.3z");
}

</style>
