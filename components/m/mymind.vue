<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yi9yvhr4d"/><path class="a_8y4lhnn"/><path class="lt6nrebbr"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymind" /></template>
<style>
.a_8y4lhnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.883 31.588s-1.452 4.04-2.079 9.38m5.343-26.433c-2.224 4.448-2.471 9.637-2.471 9.637m9.554 21.31c-.6-3.126-1.398-9.334-2.446-14.02c-1.917-1.424-2.652-2.875-1.487-4.55c1.362-1.944 2.105-1.255 4.757-2.177c1.71-.592 3.09-.565 3.395 3.637c.143 2.024.815 4.336 1.47 6.18a41 41 0 0 0 1.379 3.44");
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

.lt6nrebbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.147 30.659c-2.533 1.606-3.23 3.897-3.23 3.897m2.707 9.547c2.203-2.249 4.55-5.716 6.082-7.517");
}

.yi9yvhr4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.277 38.029a22 22 0 0 1-.412-4.345c0-9.138-4.999-9.64-9.137-12.103c-4.14-2.472-1.98-14.467-10.32-14.467c-8.278 0-12.847 9.522-12.847 15.945c0 4.677 2.133 7.991 5.322 8.529c1.182.197 2.517.018 3.941-.618");
}

</style>
