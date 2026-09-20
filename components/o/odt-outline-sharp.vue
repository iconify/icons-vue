<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2txvfbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:odt-outline-sharp" /></template>
<style>
.t2txvfbyn {
  fill: currentColor;
  d: path("M5 15h4V9H5zm1.5-1.5v-3h1v3zM10 15h3.25l.75-.75v-4.5L13.25 9H10zm1.5-1.5v-3h1v3zm4.75 1.5h1.5v-4.5H19V9h-4v1.5h1.25zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
