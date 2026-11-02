<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w21_9jsim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-fill-sharp" /></template>
<style>
.w21_9jsim {
  fill: currentColor;
  d: path("m2.293 8.293l6-6a1 1 0 0 1 1.414 0L13 5.586l2.293-2.293a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414L18.414 11l3.293 3.293a1 1 0 0 1 0 1.414l-6 6a1 1 0 0 1-1.414 0L11 18.414l-2.293 2.293A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707L5.586 13L2.293 9.707a1 1 0 0 1 0-1.414M11.586 7L11 6.414L9.707 7.707a.999.999 0 1 1-1.414-1.414L9.586 5L9 4.414L4.414 9L7 11.586ZM15 19.586L19.586 15L19 14.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 13L17 12.414L12.414 17Z");
}

</style>
