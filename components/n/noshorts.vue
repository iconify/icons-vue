<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ak2r2s1cz"/><circle class="cpk0fnbgt"/><path class="eh9kovbjb"/><path class="a2i73nbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noshorts" /></template>
<style>
.a2i73nbbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.532 22.703l1.967 1.967l.719-.416zm-4.033 1.623v3.807l2.414-1.393z");
}

.ak2r2s1cz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.201 39.201L8.799 8.799");
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

.eh9kovbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.227 8.691a5.6 5.6 0 0 0-2.47.653l-10.175 5.41L34.02 31.192c1.897-1.56 2.73-4.186 1.766-6.508a5.59 5.59 0 0 0-5.277-3.46c-.339.006-.457-.442-.159-.6l2.442-1.297c2.577-1.37 3.877-4.479 2.758-7.174a5.59 5.59 0 0 0-5.323-3.461ZM13.981 16.81c-1.897 1.56-2.73 4.185-1.766 6.507a5.59 5.59 0 0 0 5.278 3.461c.338-.006.457.441.158.6l-2.441 1.297c-2.578 1.37-3.878 4.478-2.758 7.174a5.59 5.59 0 0 0 7.793 2.808l10.174-5.41L13.98 16.808");
}

</style>
