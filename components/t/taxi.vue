<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f60dn5g-s"/><path class="xs1bccc7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taxi" /></template>
<style>
.f60dn5g-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.362 19.5v9m-8.493-9l5.963 9m0-9l-5.963 9m-14.231-9h5.963m-2.982 9v-9m7.957 6.019h-3.988m-.987 2.981l2.981-9l2.981 9");
}

.xs1bccc7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.665 15.09h24.67a4.344 4.344 0 0 1 4.221 3.315l2.881 11.819a2.172 2.172 0 0 1-2.11 2.686H6.673a2.172 2.172 0 0 1-2.11-2.686l2.88-11.819a4.344 4.344 0 0 1 4.221-3.315Z");
}

</style>
