<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bg8t_kb3s"/><path class="o762bivze"/><ellipse class="jlvz4-b3w"/><path class="h2dk3ib3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundcorset-tuner-and-metronome" /></template>
<style>
.bg8t_kb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.7 23.788l3.8-1.145m-7.097-5.091l3.108-2.499m-8.745-1.837l1.795-3.559M24 11.851V7.862m-6.797 5.459l-1.764-3.58m-3.779 7.863l-3.066-2.55M4.5 22.696l3.863.965");
}

.h2dk3ib3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.185 34.415V15.053c0 4.258 6.319 3.92 6.319 10.002c0 2.467-.769 3.599-1.537 4.114");
}

.jlvz4-b3w {
  cx: 20.841px;
  cy: 34.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.345px;
  ry: 3.924px;
}

.o762bivze {
  fill: currentColor;
  d: path("M41.421 18.05c.414 0 .745.34.745.75s-.33.75-.745.75s-.755-.338-.755-.75s.342-.75.755-.75m-5.485-6.387c.414 0 .745.339.745.75s-.331.75-.745.75s-.755-.34-.755-.75s.341-.75.755-.75m-7.732-3.475c.414 0 .745.34.745.75s-.33.75-.745.75s-.755-.339-.755-.75s.342-.75.755-.75m-8.361.011c.414 0 .745.339.745.75s-.331.75-.745.75s-.755-.34-.755-.75s.34-.75.755-.75m-7.669 3.511c.414 0 .745.34.745.75s-.331.75-.745.75s-.755-.339-.755-.75s.341-.75.755-.75M6.62 18.177c.414 0 .745.339.745.75s-.33.75-.745.75s-.755-.34-.755-.75s.342-.75.755-.75");
}

</style>
