<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjt28jbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-sharp" /></template>
<style>
.rjt28jbjm {
  fill: currentColor;
  d: path("M3 19V5h18v14zm9-6.884l8-5.231V6l-8 5l-8-5v.885z");
}

</style>
