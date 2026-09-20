<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odjsmdt3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-sensor-hi-sharp" /></template>
<style>
.odjsmdt3f {
  fill: currentColor;
  d: path("M6 21V3h12v18zm6.713-13.288Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288M0 17v-7h2v7zm3-3V7h2v7zm19 0V7h2v7zm-3 3v-7h2v7z");
}

</style>
