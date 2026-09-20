<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5pbzgpay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vo2-max-sharp" /></template>
<style>
.b5pbzgpay {
  fill: currentColor;
  d: path("M13 20v-6h4.5v6zm1.5-1.5H16v-3h-1.5zm4 3.5v-3.75h3v-.75h-3V16H23v3.75h-3v.75h3V22zM1 20V9.525L8 4V1h2v3l7 5.5V13h-5v7h-2V6.55l-1-.8l-1 .8L8.05 20z");
}

</style>
