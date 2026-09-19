<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-24.069 25.416 28.041)" class="ev-y6z3lu"/><ellipse transform="rotate(-24.069 24.258 25.45)" class="brxnyh4dr"/><path class="mbji8xf5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yandex-disk" /></template>
<style>
.brxnyh4dr {
  cx: 24.258px;
  cy: 25.449px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.828px;
  ry: 8.63px;
}

.ev-y6z3lu {
  cx: 25.416px;
  cy: 28.041px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.065px;
  ry: 3.646px;
}

.mbji8xf5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.15 33.858c-2.309-5.773 2.09-8.164 4.504-11.588c3.432-4.866 2.5-7.91 9.675-10.612c6.677-2.514 8.617.543 13.284.384c4.5-.154 8.288-.538 11.914 3.517");
}

</style>
