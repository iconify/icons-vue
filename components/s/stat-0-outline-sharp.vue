<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnc0zpvjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-0-outline-sharp" /></template>
<style>
.pnc0zpvjb {
  fill: currentColor;
  d: path("m12 19l-7-7l7-7l7 7zm0-2.85L16.15 12L12 7.85L7.85 12zM12 12");
}

</style>
