<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhjf6rbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stethoscope-fill-round" /></template>
<style>
.mhjf6rbhc {
  fill: currentColor;
  d: path("M6 5a1 1 0 0 1-1.867.498A1 1 0 0 0 4 6v5a3 3 0 1 0 6 0V6a1 1 0 0 0-.133-.502A1 1 0 0 1 8 5V3a1 1 0 0 1 2 0v.171A3 3 0 0 1 12 6v5a5.01 5.01 0 0 1-3.923 4.884A5 5 0 0 0 18 15v-2.171a3 3 0 1 1 2 0V15a7 7 0 0 1-13.942.912A5.01 5.01 0 0 1 2 11V6c0-1.27.803-2.405 2-2.829V3a1 1 0 0 1 2 0Z");
}

</style>
