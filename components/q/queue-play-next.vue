<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrxlnjb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:queue-play-next" /></template>
<style>
.yrxlnjb7a {
  fill: currentColor;
  d: path("M11.5 14.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zm8 7.23l-.73-.73l3-3l-3-3l.73-.73L23.23 18zM9 20v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V12h-4v6h-2.23v2z");
}

</style>
