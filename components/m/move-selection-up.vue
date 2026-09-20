<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utdx32bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-up" /></template>
<style>
.utdx32bqw {
  fill: currentColor;
  d: path("M6.962 13.077V3h10.077v10.077zm8.846 3.962v-1.231h1.23v1.23zm-8.846 0v-1.231h1.23v1.23zM15.808 21v-1.23h1.23V21zm-4.424 0v-1.23h1.231V21zm-4.423 0v-1.23h1.231V21z");
}

</style>
