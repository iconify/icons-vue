<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="cddfb_bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:usagedirect" /></template>
<style>
.cddfb_bws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 36.5v-25m6 25V16.937M24 36.5V13.928M30 36.5V22.267M36 36.5V16.73M3.199 18.545s12.285-1.676 18.408 6.135c6.721 8.575 11.802 3.652 17.17 4.154c4.212.394 5.765 1.532 5.765 1.532");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
