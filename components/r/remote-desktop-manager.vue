<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j0hbj-sbj"/><path class="d6iw6abyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:remote-desktop-manager" /></template>
<style>
.d6iw6abyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.487 22.382H41.5a2 2 0 0 1 2 2v11.766a2 2 0 0 1-2 2H23.06a2 2 0 0 1-2-2v-1.013");
}

.j0hbj-sbj {
  width: 35.987px;
  height: 25.284px;
  x: 4.5px;
  y: 9.851px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
