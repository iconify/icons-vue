<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8-hmvbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:planner-banner-ad-pt-outline-sharp" /></template>
<style>
.x8-hmvbgs {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4H6zm1-2h10l-3.45-4.5l-2.3 3l-1.55-2zm-1 2V4z");
}

</style>
