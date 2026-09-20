<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j96fpbbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:r-mobiledata-outline-sharp" /></template>
<style>
.j96fpbbdt {
  fill: currentColor;
  d: path("M2 10V2h7v5.2H7.8L9 10H7L5.85 7.35H4V10zm2-4.65h3V4H4z");
}

</style>
