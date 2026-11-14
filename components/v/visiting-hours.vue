<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hf65yntzl"/><path class="nzaaem63d"/><path class="y3o2ivj7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visiting-hours" /></template>
<style>
.hf65yntzl {
  d: path("M4.5 21.5v-19H17v9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzaaem63d {
  d: path("M11.5 18.075v.082q0 .118-.019.235q-.018.117-.055.23q-.036.112-.09.218q-.054.105-.124.201q-.07.095-.153.179q-.084.083-.18.153t-.202.122q-.105.054-.218.09l-4 1.285q-.084.027-.171.044q-.086.017-.174.024q-.089.006-.177.003q-.088-.004-.175-.018t-.172-.038t-.167-.058t-.158-.078q-.077-.043-.149-.095q-.071-.052-.136-.112q-.064-.06-.122-.127t-.106-.141q-.049-.073-.089-.152t-.071-.162t-.051-.168t-.031-.174t-.01-.176V4.558q0-.088.01-.176t.031-.174t.051-.168q.031-.083.071-.162t.089-.152t.106-.141t.122-.127t.136-.112q.072-.052.149-.095t.158-.078t.167-.058t.172-.038t.175-.018t.177.003t.174.024t.171.044l4 1.285q.113.036.218.09q.106.053.202.122q.096.07.18.153q.083.084.153.179q.07.096.124.201t.09.218q.037.113.055.23t.019.235v12.032M9 12.5h.01m5.24 5.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

.y3o2ivj7e {
  d: path("M18 16.25V18l1.25 1");
}

</style>
