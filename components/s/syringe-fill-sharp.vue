<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehe4-rwbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-fill-sharp" /></template>
<style>
.ehe4-rwbt {
  fill: currentColor;
  d: path("m18.707 5.293l2 2a.999.999 0 1 1-1.414 1.414L18 7.414L16.414 9l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 12.414l-6.293 6.293a1 1 0 0 1-1.414 0L8 17.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414L6.586 16l-1.293-1.293a1 1 0 0 1 0-1.414L11.586 7l-.293-.293a.999.999 0 1 1 1.414-1.414L15 7.586L16.586 6l-1.293-1.293a.999.999 0 1 1 1.414-1.414ZM13 8.414L10.414 11L13 13.586L15.586 11Z");
}

</style>
