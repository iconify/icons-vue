<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cup2v--mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trip-sharp" /></template>
<style>
.cup2v--mh {
  fill: currentColor;
  d: path("M18 21V6h4v15zM10 6h4V4h-4zM8 21V2h8v19zm-6 0V6h4v15z");
}

</style>
