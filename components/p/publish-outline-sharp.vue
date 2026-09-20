<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl6sv1blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:publish-outline-sharp" /></template>
<style>
.vl6sv1blc {
  fill: currentColor;
  d: path("M11 20v-8.15l-2.6 2.6L7 13l5-5l5 5l-1.4 1.45l-2.6-2.6V20zM4 9V4h16v5h-2V6H6v3z");
}

</style>
