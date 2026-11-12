<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-vhzebve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-corner-fill-sharp" /></template>
<style>
.q-vhzebve {
  fill: currentColor;
  d: path("m4.414 5l-1-1h17.172l-6 6H9.414ZM2 19V5.414l6.293 6.293A1 1 0 0 0 9 12h3v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m14.414-8L22 5.414V11a1 1 0 0 1-1 1h-5.586Zm3.294 7.293l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415M16 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
