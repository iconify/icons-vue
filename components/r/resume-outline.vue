<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf2ees6og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:resume-outline" /></template>
<style>
.rf2ees6og {
  fill: currentColor;
  d: path("M7.23 16.616V7.385h1v9.23zm3.386 0L18.327 12l-7.712-4.615zm1-1.814V9.198L16.298 12zm0-2.802");
}

</style>
