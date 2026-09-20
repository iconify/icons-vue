<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on_yvhu4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tooltip-outline-sharp" /></template>
<style>
.on_yvhu4x {
  fill: currentColor;
  d: path("m12 22l-2.675-4H2V2h20v16h-7.325zm0-3.6l1.6-2.4H20V4H4v12h6.4zm0-8.4");
}

</style>
