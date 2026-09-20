<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="avga_6bmx"/><path class="y-p9nqbmq"/><path class="s1_15g5ie"/><path class="x-s3w7p4x"/><path class="uchnwta9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rider" /></template>
<style>
.avga_6bmx {
  d: path("M36.07 29.808a5.408 5.408 0 0 1 6.195 5.352a5.409 5.409 0 1 1-10.817 0a5.41 5.41 0 0 1 2.09-4.27");
}

.s1_15g5ie {
  d: path("m18.97 22.282l.071.867l11.007 8.22l.895-1.249l1.664-.208l2.491-1.584l1.56-.911l-2.374-3.346l-3.718-2.468l-12.079-5.199l.113 1.382");
}

.uchnwta9b {
  d: path("m14.016 7.43l7.923 6.558l9.813 8.401M16.444 9.54l4.328 7.847m20.23 7.963l-2.74.28l-2.197-1.58l-.133 2.343");
}

.x-s3w7p4x {
  d: path("m30.824 30.285l-4.644-5.774l8.712.416M15.917 21.05A5.408 5.408 0 0 1 5.5 19.01a5.408 5.408 0 0 1 10.469-1.91m9.511-.08l.824-.638l4.692.035l7.703 3.106l3.8 6.05l-.555.182l-.95-.407l-2.847-3.697");
}

.y-p9nqbmq {
  d: path("m32.607 29.912l5.376 5.652l.782-1.622l-3.667-5.614M11.664 15.985l11.58 3.004l.756 5.32l-15.053-6.07z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
