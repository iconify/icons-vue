<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri00qrbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-fill-sharp" /></template>
<style>
.ri00qrbjv {
  fill: currentColor;
  d: path("M4 17V6c0-.265.105-.52.293-.707l3-3A1 1 0 0 1 8 2h8c.265 0 .52.105.707.293l3 3A1 1 0 0 1 20 6v11a1 1 0 0 1-1 1h-1.382l1.276 2.553a1 1 0 1 1-1.788.894L15.382 18H8.618l-1.724 3.447a1 1 0 1 1-1.788-.894L6.382 18H5a1 1 0 0 1-1-1M8.414 4L6 6.414V9h12V6.414L15.586 4Zm.596 9H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m6 0H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
