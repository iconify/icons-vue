<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlbnh-bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mimo-sharp" /></template>
<style>
.qlbnh-bao {
  fill: currentColor;
  d: path("M6 21v-2l1-1H2V3h20v15h-5l1 1v2z");
}

</style>
