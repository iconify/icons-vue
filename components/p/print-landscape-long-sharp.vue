<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdj_q-d_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-landscape-long-sharp" /></template>
<style>
.vdj_q-d_a {
  fill: currentColor;
  d: path("M14 4h3v1h3.05L21 6.35L18.225 14H2.6l-.95-1.35L4.425 5H7V4h3v1h4zM4 16h15.725L21 12.475V19H4z");
}

</style>
