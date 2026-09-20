<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9_qk5bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:piano-sharp" /></template>
<style>
.x9_qk5bmp {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h3.25v-4.5H7V5H5zm10.75 0H19V5h-2v9.5h-1.25zm-6 0h4.5v-4.5H13V5h-2v9.5H9.75z");
}

</style>
