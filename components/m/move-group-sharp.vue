<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdpwyc_uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-group-sharp" /></template>
<style>
.zdpwyc_uf {
  fill: currentColor;
  d: path("M6.5 17v-3.115h1V16h12V6h-12v2.116h-1V3h14v14zm-3 3V6.616h1V19h12.385v1zm8.923-5.327l-.688-.689l2.44-2.484H6.5v-1h7.675l-2.44-2.484l.688-.689L16.096 11z");
}

</style>
