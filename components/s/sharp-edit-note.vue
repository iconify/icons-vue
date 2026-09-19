<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0it2b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-edit-note" /></template>
<style>
.mi0it2b8d {
  fill: currentColor;
  d: path("M3 10h11v2H3zm0-2h11V6H3zm0 8h7v-2H3zm15.01-3.13l1.41-1.41l2.12 2.12l-1.41 1.41zm-.71.71l-5.3 5.3V21h2.12l5.3-5.3z");
}

</style>
