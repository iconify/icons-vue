<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dcal7huld"/><rect class="ftmvvjbqo"/><path class="nguvw3byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toffeeshare" /></template>
<style>
.dcal7huld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.209 15.858l-7.362 9.067m16.754-9.067l-13.194 16.25m16.754-9.066L26.8 32.109");
}

.ftmvvjbqo {
  width: 20.314px;
  height: 16.251px;
  x: 13.847px;
  y: 15.858px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.047px;
  ry: 3.047px;
}

.nguvw3byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.839 19.36l-2.422-4.56a3.005 3.005 0 0 0-5.306 2.822l1.343 2.125l-2.04 2.04a3.12 3.12 0 0 0 0 4.415l2.049 2.05l-1.344 2.126a3.005 3.005 0 0 0 5.306 2.822l2.414-4.56m20.322-9.28l2.422-4.56a3.005 3.005 0 0 1 5.306 2.822l-1.343 2.125l2.04 2.04a3.12 3.12 0 0 1 0 4.415l-2.049 2.05l1.344 2.126a3.005 3.005 0 0 1-5.306 2.822l-2.414-4.56");
}

</style>
