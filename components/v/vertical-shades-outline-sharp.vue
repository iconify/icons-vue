<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnwykryte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-shades-outline-sharp" /></template>
<style>
.lnwykryte {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm4-2h2V5H6zm4 0h4V5h-4zm6 0h2V5h-2zM6 19V5zm12 0V5z");
}

</style>
