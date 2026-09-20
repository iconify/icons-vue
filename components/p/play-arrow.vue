<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmyft4pud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-arrow" /></template>
<style>
.gmyft4pud {
  fill: currentColor;
  d: path("M8 19V5l11 7z");
}

</style>
