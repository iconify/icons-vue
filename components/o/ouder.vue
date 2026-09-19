<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i1exvt6cm"/><path class="db2cfvbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ouder" /></template>
<style>
.db2cfvbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.007 25.196c-2.211 3.253-5.243 6.316-12.129 6.316");
}

.i1exvt6cm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.98 6.627v4.995c0 .622.504 1.126 1.126 1.126h5.8c.623 0 1.127.505 1.127 1.127v4.095c0 .622.505 1.127 1.127 1.127h3.195c.622 0 1.127.504 1.127 1.126v7.552c0 .622-.505 1.126-1.127 1.126h-2.816c-.622 0-1.127.504-1.127 1.127v4.713c0 .622-.504 1.127-1.126 1.127h-2.39c-.622 0-1.126.504-1.126 1.126v4.38c0 .622-.505 1.126-1.127 1.126h-4.332a1.126 1.126 0 0 1-1.127-1.126v-4.38c0-.622-.504-1.126-1.126-1.126h-.116c-.622 0-1.126.504-1.126 1.126v4.38c0 .622-.505 1.126-1.127 1.126h-4.332a1.126 1.126 0 0 1-1.127-1.126v-4.38c0-.622-.504-1.126-1.126-1.126h-2.39a1.126 1.126 0 0 1-1.127-1.127v-4.713c0-.622-.504-1.127-1.126-1.127H7.645a1.126 1.126 0 0 1-1.127-1.126v-7.552c0-.622.505-1.126 1.127-1.126h3.195c.622 0 1.126-.505 1.126-1.127v-4.095c0-.622.505-1.127 1.127-1.127h5.8c.623 0 1.127-.504 1.127-1.126V6.626c0-.622.505-1.126 1.127-1.126h5.706c.622 0 1.126.504 1.126 1.126Z");
}

</style>
