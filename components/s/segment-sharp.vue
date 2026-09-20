<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd479hbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:segment-sharp" /></template>
<style>
.gd479hbkb {
  fill: currentColor;
  d: path("M9 18v-2h12v2zm0-5v-2h12v2zM3 8V6h18v2z");
}

</style>
