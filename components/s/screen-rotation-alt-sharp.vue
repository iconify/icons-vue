<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdb0axbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screen-rotation-alt-sharp" /></template>
<style>
.cdb0axbin {
  fill: currentColor;
  d: path("M13.6 22.8L3.75 13H6.6l7 7l5-5H16v-2h6v6h-2v-2.6zM2 11V5h2v2.6l6.4-6.4l9.85 9.8H17.4l-7-7l-5 5H8v2z");
}

</style>
