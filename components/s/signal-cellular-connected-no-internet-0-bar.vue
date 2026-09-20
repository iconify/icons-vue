<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhe3ubbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-connected-no-internet-0-bar" /></template>
<style>
.vhe3ubbeg {
  fill: currentColor;
  d: path("M2 22L22 2v6h-2V6.825L6.825 20H18v2zm18.288-.288Q20 21.426 20 21t.288-.712T21 20t.713.288T22 21t-.288.713T21 22t-.712-.288M20 18v-8h2v8z");
}

</style>
