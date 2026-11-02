<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nktdr8bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-down-bulk-sharp" /></template>
<style>
.nktdr8bdd {
  fill: currentColor;
  d: path("m9 11.586l3.293-3.293a1 1 0 0 1 1.414 0L20 14.586V11a1 1 0 0 1 2 0v6a.997.997 0 0 1-1 1h-6a1 1 0 0 1 0-2h3.586L13 10.414l-3.293 3.293a1 1 0 0 1-1.414 0l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>
