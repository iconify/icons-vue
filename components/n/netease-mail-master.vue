<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="br27u13qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netease-mail-master" /></template>
<style>
.br27u13qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.666 7.354l-3.527 25.299M7.945 15.117L5.5 32.653m37-17.536l-2.445 17.536M25.222 15.117l-2.445 17.536m11.084-17.536l-3.559 25.529");
}

</style>
