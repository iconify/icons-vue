<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u30wygbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-css" /></template>
<style>
.u30wygbij {
  fill: currentColor;
  d: path("M9.5 15v-2H11v.5h2v-1H9.5V9h5v2H13v-.5h-2v1h3.5V15zm6.5 0h5v-3.5h-3.5v-1h2v.5H21V9h-5v3.5h3.5v1h-2V13H16zm-8-4V9H3v6h5v-2H6.5v.5h-2v-3h2v.5z");
}

</style>
