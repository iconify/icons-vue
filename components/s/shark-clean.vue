<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="b8ui95zfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shark-clean" /></template>
<style>
.b8ui95zfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.325 18.779l-1.488 8.442m.613-3.482c.206-1.166 1.318-2.11 2.484-2.11s1.944.944 1.738 2.11l-.614 3.482m9.056-3.482c.206-1.166 1.317-2.11 2.483-2.11m-2.111-.001l-.986 5.593m5.68-8.442l-1.489 8.442m.317-1.793l4.492-3.803m-3.062 2.593l2.476 2.991M9.5 26.296c.399.674 1.004.925 1.907.925h1.25c1.163 0 2.273-.945 2.478-2.11S14.565 23 13.401 23h-1.38c-1.164 0-1.94-.945-1.735-2.11c.206-1.166 1.315-2.111 2.478-2.111h1.25c.903 0 1.508.25 1.907.925m11.841 5.406c-.206 1.166-1.317 2.111-2.483 2.111s-1.944-.945-1.738-2.11l.242-1.372c.205-1.166 1.317-2.11 2.482-2.11s1.944.944 1.739 2.11m-.614 3.482l.986-5.593");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
