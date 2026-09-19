<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffm1robhm"/><circle class="o63e5cbjl"/><circle class="vbbgliskk"/><path class="w4w14_ibg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:woof-tech" /></template>
<style>
.ffm1robhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.448c4.443 0 17.917 0 18.298-9.78c.12-3.063.255-5.966.177-8.736l.025.016c0-10.49-4.804-15.867-7.8-18.127c-.98-.738-2.313-.325-2.9.752c-1.01 1.855-2.615 5.536-2.615 8.782h0c-1.762-.08-3.53-.092-5.185-.092s-3.423.012-5.185.092h0c0-3.246-1.605-6.927-2.615-8.782c-.587-1.077-1.92-1.49-2.9-.752c-2.996 2.26-7.8 7.638-7.8 18.127l.025-.016c-.078 2.77.057 5.673.176 8.736c.382 9.78 13.856 9.78 18.299 9.78");
}

.o63e5cbjl {
  cx: 12.032px;
  cy: 29.307px;
  r: 0.75px;
  fill: currentColor;
}

.vbbgliskk {
  cx: 35.968px;
  cy: 29.307px;
  r: 0.75px;
  fill: currentColor;
}

.w4w14_ibg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.136v3.157a3.237 3.237 0 0 0 3.237 3.236h0a3.237 3.237 0 0 0 3.236-3.237v-5.708M24 31.293a3.237 3.237 0 0 1-3.237 3.236h0a3.237 3.237 0 0 1-3.236-3.237h0v-5.708");
}

</style>
