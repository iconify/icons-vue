<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjif96bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-footer-outline-sharp" /></template>
<style>
.gjif96bjc {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V3h18v14zm2-2h14V5H5zm0 0V5z");
}

</style>
