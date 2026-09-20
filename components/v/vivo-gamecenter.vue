<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehy6yh79s"/><path class="bi7-zcclo"/><circle class="zk_-10b_n"/><path class="x_0gibbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vivo-gamecenter" /></template>
<style>
.bi7-zcclo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.175 15.026zc.978-2.56 4.244-3.302 6.232-1.416l25.036 23.748c2.393 2.27 6.323.379 6.043-2.907l-1.64-19.233a6.087 6.087 0 0 0-6.065-5.57H24");
}

.ehy6yh79s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.846 15.218l-.047-.127c-.962-2.58-4.246-3.34-6.243-1.446l-25 23.713c-2.392 2.27-6.322.379-6.042-2.907l1.64-19.233a6.087 6.087 0 0 1 6.065-5.57H24");
}

.x_0gibbfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.534 27.415v-5.516m-2.758 2.758h5.516");
}

.zk_-10b_n {
  cx: 13.788px;
  cy: 24.657px;
  r: 2.758px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
