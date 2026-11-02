<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj_0cp0da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-fill" /></template>
<style>
.cj_0cp0da {
  fill: currentColor;
  d: path("m3.293 7.293l4-4a2.414 2.414 0 0 1 3.414 0L13 5.586l1.293-1.293a2.414 2.414 0 0 1 3.414 0l2 2a2.414 2.414 0 0 1 0 3.414L18.414 11l2.293 2.293a2.414 2.414 0 0 1 0 3.414l-4 4a2.414 2.414 0 0 1-3.414 0L11 18.414l-2.293 2.293A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707L5.586 13l-2.293-2.293a2.414 2.414 0 0 1 0-3.414M11.586 7L11 6.414L9.707 7.707a.999.999 0 1 1-1.414-1.414L9.586 5l-.293-.293a.414.414 0 0 0-.586 0l-4 4a.414.414 0 0 0 0 .586L7 11.586Zm3.121 12.293a.414.414 0 0 0 .586 0l4-4a.414.414 0 0 0 0-.586L19 14.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 13L17 12.414L12.414 17Z");
}

</style>
