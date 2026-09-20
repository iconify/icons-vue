<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xou2fkb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:partner-reports-outline" /></template>
<style>
.xou2fkb2c {
  fill: currentColor;
  d: path("M11.288 16.713Q11 16.425 11 16t.288-.712T12 15t.713.288T13 16t-.288.713T12 17t-.712-.288M11 13V3h2v10zm-6 8q-.825 0-1.412-.587T3 19v-3h2v3h14v-3h2v3q0 .825-.587 1.413T19 21z");
}

</style>
