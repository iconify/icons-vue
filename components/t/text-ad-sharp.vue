<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsia2hbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-ad-sharp" /></template>
<style>
.fsia2hbyl {
  fill: currentColor;
  d: path("M2 20V4h20v16zm3-3h14v-2H5zm0-4h14v-2H5zm0-4h10V7H5z");
}

</style>
