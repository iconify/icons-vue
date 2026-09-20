<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgajco8co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-headline-sharp" /></template>
<style>
.hgajco8co {
  fill: currentColor;
  d: path("M4 15v-2h16v2zm0 4v-2h16v2zm0-8V9h16v2zm0-4V5h16v2z");
}

</style>
