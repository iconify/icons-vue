<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbux6n5dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-numbers-fill-round" /></template>
<style>
.zbux6n5dh {
  fill: currentColor;
  d: path("M3 2h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 4h10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m-.707 8.293l2-2A1 1 0 0 1 6 13v8a1 1 0 0 1-2 0v-5.586l-.293.293a.999.999 0 1 1-1.414-1.414m11.539 1.262L10.869 20H13a1 1 0 0 1 0 2H9a1 1 0 0 1-.832-1.555l3.801-5.701a1 1 0 0 0-.262-.451a1 1 0 0 0-1.094-.215A.99.99 0 0 0 10 15a1 1 0 0 1-2 0a3 3 0 1 1 6 0a1 1 0 0 1-.168.555M17 12h4a.998.998 0 0 1 .8 1.6l-1.902 2.537A3.001 3.001 0 0 1 19 22h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 0-2h-1a.998.998 0 0 1-.8-1.6L19 14h-2a1 1 0 0 1 0-2");
}

</style>
