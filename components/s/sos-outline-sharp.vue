<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfkea-bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sos-outline-sharp" /></template>
<style>
.qfkea-bmy {
  fill: currentColor;
  d: path("M8.5 17V7h7v10zM1 17v-2h4v-2H1V7h6v2H3v2h4v6zm16 0v-2h4v-2h-4V7h6v2h-4v2h4v6zm-6.5-2h3V9h-3z");
}

</style>
