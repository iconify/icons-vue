<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ayrxvib9v"/><path class="gu2djrbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallet-plus" /></template>
<style>
.ayrxvib9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.559 18.675l-1.691 6.65l-1.691-6.65l-1.691 6.65l-1.691-6.65m13.106 0v6.65m1.691-6.65v6.65m7.652-5.777v4.946c0 .459.379.831.846.831h.253m-1.987-4.406h1.776m-3.689 3.567c-.291.501-.84.839-1.47.839c-.933 0-1.69-.744-1.69-1.662v-1.081c0-.918.757-1.663 1.69-1.663s1.692.745 1.692 1.663v.54h-3.382m8.54-2.203h3.382m-1.691-1.662v3.325m-15.304 1.08a1.67 1.67 0 0 1-1.678 1.663h-.59c-.613 0-1.111-.494-1.111-1.102s.498-1.101 1.112-1.101h2.27");
}

.gu2djrbej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.25 21.356c.408-.401.693-.436 1.48-.436c.893 0 1.48.386 1.48 1.43v2.975M5.5 29.5h7v13m0-37v9h-7m37 0h-15v-9m0 37v-13h15");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
