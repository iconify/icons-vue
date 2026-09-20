<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u31irnb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-32-filled" /></template>
<style>
.u31irnb0f {
  fill: currentColor;
  d: path("M19.5 28a1 1 0 1 1 0 2h-7a1 1 0 1 1 0-2zm4-4a1 1 0 1 1 0 2h-15a1 1 0 1 1 0-2zm1.5-4a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zm0-4a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zM15.998 2c.509 0 .803.386 1.116.72c.76.811 2.48 2.725 4.206 5.222c1.211 1.751 2.46 3.838 3.364 6.058H7.313c.902-2.22 2.152-4.307 3.363-6.058a47 47 0 0 1 4.206-5.222c.312-.333.611-.72 1.116-.72");
}

</style>
