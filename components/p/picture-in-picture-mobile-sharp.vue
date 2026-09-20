<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evkeupb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-mobile-sharp" /></template>
<style>
.evkeupb5s {
  fill: currentColor;
  d: path("M19 21H5V3h14zm-2.039-8.308V5H11.27v7.692z");
}

</style>
