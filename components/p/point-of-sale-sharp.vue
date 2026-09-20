<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqxrgkbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:point-of-sale-sharp" /></template>
<style>
.aqxrgkbpm {
  fill: currentColor;
  d: path("M5 8V2h14v6zm2-2h10V4H7zM2 22v-3h20v3zm0-4l4-9h12l4 9zm6-2h2v-1H8zm0-2h2v-1H8zm0-2h2v-1H8zm3 4h2v-1h-2zm0-2h2v-1h-2zm0-2h2v-1h-2zm3 4h2v-1h-2zm0-2h2v-1h-2zm0-2h2v-1h-2z");
}

</style>
