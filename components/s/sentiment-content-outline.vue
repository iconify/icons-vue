<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yug9babmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-content-outline" /></template>
<style>
.yug9babmx {
  fill: currentColor;
  d: path("M9.308 15.192h5.384v-.884H9.308zm-.712-6.384q-.665 0-1.218.344t-.964.871l.75.498q.288-.336.648-.58t.784-.243t.785.234t.648.564l.75-.498q-.412-.521-.971-.856q-.56-.334-1.212-.334m6.808 0q-.665 0-1.218.344t-.965.871l.75.498q.289-.33.648-.574t.785-.243t.787.24t.646.577l.75-.498q-.412-.527-.972-.871t-1.211-.344M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708m9.182-2.617Q20 15.35 20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325");
}

</style>
