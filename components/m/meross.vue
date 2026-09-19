<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="t6fs68b4d"/><path class="dw6-5-b6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meross" /></template>
<style>
.dw6-5-b6t {
  d: path("M26.884 37.308V19.956s.43-9.264-10.69-9.264c-11.154 0-10.691 9.264-10.691 9.264v17.352h5.43V23.229s-.225-7.515 5.194-7.515c5.403 0 5.194 7.515 5.194 7.515v14.079z");
}

.t6fs68b4d {
  d: path("M26.841 19.006c1.504-3.192 3.251-3.302 4.9-3.292c5.403.03 5.194 7.516 5.194 7.516v14.078h5.563V19.956s.43-9.264-10.691-9.264c-3.41 0-5.116 1.03-6.948 3.38");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
