<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uimgwkbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:planner-banner-ad-pt-sharp" /></template>
<style>
.uimgwkbpu {
  fill: currentColor;
  d: path("M4 22V2h16v20zm3-4h10l-3.45-4.5l-2.3 3l-1.55-2z");
}

</style>
