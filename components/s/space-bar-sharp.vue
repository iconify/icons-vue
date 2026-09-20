<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4qfs0b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-bar-sharp" /></template>
<style>
.p4qfs0b5c {
  fill: currentColor;
  d: path("M5 14V9h1v4h12V9h1v5z");
}

</style>
