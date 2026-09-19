<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo76n9bso"/><path class="c2sld4byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-hdr-auto" /></template>
<style>
.bo76n9bso {
  fill: currentColor;
  d: path("M12.04 8.04h-.09l-1.6 4.55h3.29z");
}

.c2sld4byo {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m3.21 15l-.98-2.81H9.78l-1 2.81h-1.9l4.13-11h1.97l4.13 11z");
}

</style>
