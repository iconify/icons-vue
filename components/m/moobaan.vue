<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afj2g7h0c"/><path class="o05t32bzt"/><path class="lhuky3dso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moobaan" /></template>
<style>
.afj2g7h0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.779 21.476A6.78 6.78 0 0 1 24 28.254h0a6.78 6.78 0 0 1-6.778-6.778h0a6.779 6.779 0 1 1 13.557 0m5.976 14.273c-1.083-2.543-3.803-4.63-7.419-5.695h0A10.1 10.1 0 0 1 24 31.587a10.1 10.1 0 0 1-5.32-1.524c-3.616 1.06-6.339 3.144-7.428 5.684");
}

.lhuky3dso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.567 16.75L24 4.508L41.433 16.75M34.45 6.052v5.483m-2.227 27.368a1.99 1.99 0 0 1-1.99 1.99h0a1.99 1.99 0 1 1 1.99-1.99m-.135-7.66c.108 2.138-.535 4.314-1.151 5.738m-14.95 6.02l-1.202.453c-.617.232-1.631-.611-1.524-1.262l1.185-7.213c.095-.578 1.193-.992 1.647-.62l5.65 4.64c.51.419.302 1.722-.316 1.954l-1.069.403m-5.256-7.138l-.135-2.364");
}

.o05t32bzt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.1 35.749H9.94v-21.11m17.667 21.11h-6.152M37.67 14.365v21.384h-3.958");
}

</style>
