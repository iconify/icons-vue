<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzbi0lb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-right-sharp" /></template>
<style>
.qzbi0lb_g {
  fill: currentColor;
  d: path("M4 19V5h5.116v14zm7.5 2V3h1v2H20v14h-7.5v2z");
}

</style>
