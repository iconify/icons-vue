<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf6dejb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vpn-key-off-sharp" /></template>
<style>
.wf6dejb4p {
  fill: currentColor;
  d: path("M19.775 22.625L12.15 15q-.8 1.35-2.137 2.175T7 18q-2.5 0-4.25-1.75T1 12q0-1.65.8-3.025T3.95 6.8L1.375 4.225L2.8 2.8l18.4 18.4zM7 14q.825 0 1.413-.587T9 12v-.175L7.175 10H7q-.825 0-1.412.588T5 12t.588 1.413T7 14m13.825 4l-8-8H23v4h-2v4z");
}

</style>
