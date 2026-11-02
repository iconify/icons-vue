<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6z9rqr0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:terminal-fill-sharp" /></template>
<style>
.n6z9rqr0l {
  fill: currentColor;
  d: path("M2 19V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M7.707 8.293a.999.999 0 1 0-1.414 1.414L8.586 12l-2.293 2.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414ZM13 14a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Z");
}

</style>
