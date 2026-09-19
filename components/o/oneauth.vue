<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sdce84b4a"/><path class="uugywtbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oneauth" /></template>
<style>
.sdce84b4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.36 28.958c1.68-4.121-.257-9.916-4.36-9.916s-6.04 5.795-4.36 9.916M24 19.042V2.5m-3.41 2.597h3.052m1.375 20.869h3.794m-26.232-.124A21.5 21.5 0 0 1 14.928 4.508M5.562 35.063a21.4 21.4 0 0 1-1.784-3.747m35.137 8.17A21.43 21.43 0 0 1 24 45.5a21.43 21.43 0 0 1-15.293-6.388m36.67-17.406q.122 1.135.123 2.294h0a21.4 21.4 0 0 1-2.915 10.817M33.076 4.51a21.5 21.5 0 0 1 10.996 11.78");
}

.uugywtbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.304 12.117A13.01 13.01 0 0 1 37.014 24c0 7.185-5.823 13.01-13.008 13.012H24c-7.185.001-13.011-5.823-13.012-13.008V24c0-5.135 3.02-9.79 7.71-11.883");
}

</style>
