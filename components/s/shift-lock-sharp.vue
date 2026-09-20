<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u63g9u3in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shift-lock-sharp" /></template>
<style>
.u63g9u3in {
  fill: currentColor;
  d: path("M8 18v-5H3l9-11l9 11h-5v5zm-4 4v-2h16v2z");
}

</style>
