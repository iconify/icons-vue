<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x1b_otl8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:square-half-bottom-bold" /></template>
<style>
.x1b_otl8l {
  fill: currentColor;
  d: path("M200 36H56a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 24v56H60V60Zm-80 80v56h-16v-56Zm24 0h16v56h-16Zm-80 0h16v56H60Zm120 56v-56h16v56Z");
}

</style>
