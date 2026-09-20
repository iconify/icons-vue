<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9z5dj2hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-email-sharp" /></template>
<style>
.x9z5dj2hl {
  fill: currentColor;
  d: path("M5 17V3h18v14zm-4 4V6.5h2V19h16.5v2zm13-8.725l7-4.85V5l-7 4.85L7 5v2.425z");
}

</style>
