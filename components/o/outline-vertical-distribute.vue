<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbk2pjqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-vertical-distribute" /></template>
<style>
.bmbk2pjqb {
  fill: currentColor;
  d: path("M22 2v2H2V2zM7 10.5v3h10v-3zM2 20v2h20v-2z");
}

</style>
