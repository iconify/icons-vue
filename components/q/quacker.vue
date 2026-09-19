<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia1v9kb0k"/><circle class="t6-_v_8kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quacker" /></template>
<style>
.ia1v9kb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.89 23.364c9.315-.674 8.944 4.081 12.85 3.647c2.02-.224 3.76-1.823 3.76-1.823c0 8.782-5.718 16.187-11.728 16.47c-3.871.182-9.933.168-13.3 0s-8.418-2.706-8.418-9.07s4.265-6.026 4.265-10.29c0-.767-.28-1.235-.28-1.235c-3.76.28-7.09-1.029-7.539-6.06c2.544.934 5.462 0 5.462 0C10.72 9.97 15.377 6.21 20.39 6.21s9.184 4.49 9.184 9.372s-3.685 7.782-3.685 7.782Z");
}

.t6-_v_8kb {
  cx: 17.472px;
  cy: 14.722px;
  r: 2.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
