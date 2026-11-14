<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka3todqzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:music-note" /></template>
<style>
.ka3todqzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.475 19.975Q10.5 18.95 10.5 17.5V6.109l8-1.685v7.993q-.791-.417-2-.417q-3.5 0-3.5 3.5t3.5 3.5t3.5-3.5v-12q0-.078-.016-.155q-.031-.145-.115-.269q-.084-.123-.209-.204q-.125-.082-.272-.109q-.147-.028-.293.003l-9.5 2q-.062.013-.122.037q-.059.024-.114.057t-.103.076t-.088.091q-.041.05-.072.106t-.053.116q-.021.061-.032.124T9 5.5v9.121Q8.129 14 7 14q-3.5 0-3.5 3.5T7 21q1.45 0 2.475-1.025");
}

</style>
