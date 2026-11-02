<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgifcjbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stethoscope-fill-sharp" /></template>
<style>
.lgifcjbtp {
  fill: currentColor;
  d: path("M6 5a1 1 0 0 1-2 0v6a3 3 0 1 0 6 0V5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0h1a1 1 0 0 1 1 1v7a5.01 5.01 0 0 1-3.923 4.884A5 5 0 0 0 18 15v-2.171a3 3 0 1 1 2 0V15a7 7 0 0 1-13.942.912A5.01 5.01 0 0 1 2 11V4a1 1 0 0 1 1-1h1a1 1 0 0 1 2 0Z");
}

</style>
