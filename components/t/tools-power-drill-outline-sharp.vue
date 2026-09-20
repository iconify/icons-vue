<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btoklccjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-power-drill-outline-sharp" /></template>
<style>
.btoklccjd {
  fill: currentColor;
  d: path("M6 19h6v-1H6zm0-9h6V8.5H6zm0-2.5h6V6H6zM16 11V9h2V7h-2V5h3l1 1v1h3v2h-3v1l-1 1zm-4 5h-2v-5h4V5H6q-.825 0-1.412.588T4 7v2q0 .825.588 1.413T6 11h2v5H6v-3q-1.65 0-2.825-1.175T2 9V7q0-1.65 1.175-2.825T6 3h10v10h-4zm-8 5v-5h10v5zm8-2H6z");
}

</style>
