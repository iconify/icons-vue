<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p906ccbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-call-outline-sharp" /></template>
<style>
.p906ccbhh {
  fill: currentColor;
  d: path("M3.48 19V5h14v6.27l3.04-3.04v7.54l-3.04-3.04V19zm1-1h12V6h-12zm0 0V6zm5.5-2.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3z");
}

</style>
