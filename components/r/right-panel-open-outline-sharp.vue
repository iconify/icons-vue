<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do-km6blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:right-panel-open-outline-sharp" /></template>
<style>
.do-km6blh {
  fill: currentColor;
  d: path("M11.596 15.173V8.827L8.404 12zM16 19h3V5h-3zM5 19h10V5H5zm11 0h3zM4 20V4h16v16z");
}

</style>
