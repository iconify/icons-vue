<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ev4i4mfxc"/><path class="kydc9usyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myt-muzik" /></template>
<style>
.ev4i4mfxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 26.775l7.888-11.539l10.021 11.11m3.182-4.911l10.021 11.11L43.5 21.006");
}

.kydc9usyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.014 21.995l10.022 11.11l11.782-18.21l10.16 11.263");
}

</style>
