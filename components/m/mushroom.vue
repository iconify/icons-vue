<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9pyqnbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mushroom" /></template>
<style>
.i9pyqnbkt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.567 5.562Q2.75 8.041 2.75 12q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.25V19q0 2.25 3.25 2.25T15.25 19v-6.25h5.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.959-2.817-6.438Q15.806 3.25 12 3.25T5.567 5.562M10.25 19v-6.25h3.5V19q0 .75-1.75.75T10.25 19");
}

</style>
