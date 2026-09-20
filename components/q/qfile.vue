<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="urzk7htfx"/><path class="ldo48nw-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qfile" /></template>
<style>
.ldo48nw-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.696 39.683A6.804 6.804 0 0 0 43.5 32.88V18.258a6.804 6.804 0 0 0-6.804-6.804H24.731a4.45 4.45 0 0 1-2.478-.754l-2.432-1.63a4.45 4.45 0 0 0-2.478-.753h-2.97a5.46 5.46 0 0 0-3.775 1.514a4.93 4.93 0 0 0-1.508 3.963l.314 3.885");
}

.urzk7htfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.959 17.679H9.403a4.9 4.9 0 0 0-4.663 6.403l3.976 12.332a4.715 4.715 0 0 0 4.488 3.27h22.555a4.9 4.9 0 0 0 4.663-6.404l-3.975-12.333a4.715 4.715 0 0 0-4.488-3.268");
}

</style>
