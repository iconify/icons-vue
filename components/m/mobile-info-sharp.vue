<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7d98fbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-info-sharp" /></template>
<style>
.w7d98fbwp {
  fill: currentColor;
  d: path("M11 16.5h2V11h-2zm1.713-7.788Q13 8.425 13 8t-.288-.712T12 7t-.712.288T11 8t.288.713T12 9t.713-.288M5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
