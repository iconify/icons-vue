<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="carq8kbay"/><path class="s1l6smbip"/><path class="kztjpdrkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pairdrop" /></template>
<style>
.carq8kbay {
  cx: 24px;
  cy: 24.134px;
  r: 0.75px;
  fill: currentColor;
}

.kztjpdrkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.15 42.963C40.825 39.357 45.5 32.279 45.5 24c0-11.885-9.615-21.5-21.5-21.5c-11.885.134-21.5 9.749-21.5 21.634c0 8.146 4.54 15.357 11.35 18.962");
}

.s1l6smbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.609 34.55c3.739-2.003 6.143-5.876 6.143-10.416c0-6.544-5.342-11.885-11.886-11.885S11.981 17.59 11.981 24.134c0 4.54 2.538 8.413 6.277 10.416");
}

</style>
