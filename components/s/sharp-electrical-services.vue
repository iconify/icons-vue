<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q83kd7j8c"/><path class="c0xzsvhxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-electrical-services" /></template>
<style>
.c0xzsvhxu {
  fill: currentColor;
  d: path("M5 11h7V4H4v2h6v3H3v8h6v-2H5zm13 6h3v2h-3z");
}

.q83kd7j8c {
  fill: currentColor;
  d: path("M18 13h3v2h-3zm-6-1v2h-2v4h2v2h5v-8z");
}

</style>
