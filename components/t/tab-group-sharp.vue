<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdffd6b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-group-sharp" /></template>
<style>
.fdffd6b5z {
  fill: currentColor;
  d: path("M3.5 20V6.616h1V19h12.385v1zm3-3V3h14v14zm6.77-9.961h6.23V4h-6.23z");
}

</style>
