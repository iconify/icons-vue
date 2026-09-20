<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4wtzfb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:oven-outline-sharp" /></template>
<style>
.m4wtzfb5v {
  fill: currentColor;
  d: path("M16.713 6.713Q17 6.425 17 6t-.288-.712T16 5t-.712.288T15 6t.288.713T16 7t.713-.288m-4 0Q13 6.426 13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7t.713-.288m-4 0Q9 6.426 9 6t-.288-.712T8 5t-.712.288T7 6t.288.713T8 7t.713-.288M5 10v9h14v-9zm5 4h4v-2h-4zm-7 7V3h18v18zm9-11");
}

</style>
