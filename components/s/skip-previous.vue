<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4pm-6_gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:skip-previous" /></template>
<style>
.h4pm-6_gh {
  fill: currentColor;
  d: path("M5.5 18V6h2v12zm13 0l-9-6l9-6z");
}

</style>
