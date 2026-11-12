<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-9bmcbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-fill-sharp" /></template>
<style>
.q-9bmcbaj {
  fill: currentColor;
  d: path("M13 7.829V11h5a1 1 0 0 1 1 1v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L17 17.586V13H7v4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.413.001h-.001l-3-3.001a.999.999 0 1 1 1.414-1.414L5 17.586V12a1 1 0 0 1 1-1h5V7.829a3 3 0 1 1 2 0");
}

</style>
