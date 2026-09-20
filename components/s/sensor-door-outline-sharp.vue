<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln9k5cckw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensor-door-outline-sharp" /></template>
<style>
.ln9k5cckw {
  fill: currentColor;
  d: path("M5 21V3h14v18zm1-1h12V4H6zm9.498-7q.416 0 .709-.291t.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293M5 20h1V4H5z");
}

</style>
