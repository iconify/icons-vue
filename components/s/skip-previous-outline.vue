<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fenz21hyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:skip-previous-outline" /></template>
<style>
.fenz21hyb {
  fill: currentColor;
  d: path("M5.5 18V6h2v12zm13 0l-9-6l9-6zm-2-3.75v-4.5L13.1 12z");
}

</style>
