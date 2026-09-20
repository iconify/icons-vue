<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6r5wzbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tooltip-2-outline-sharp" /></template>
<style>
.w6r5wzbwb {
  fill: currentColor;
  d: path("M6 14h8v-2H6zm0-3h12V9H6zm0-3h12V6H6zm6 14l-2.675-4H2V2h20v16h-7.325zm0-3.6l1.6-2.4H20V4H4v12h6.4zm0-8.4");
}

</style>
