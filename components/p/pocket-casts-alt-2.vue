<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gywiubbtm"/><path class="wx8b-qb_g"/><path class="jq0jyk1on"/><circle class="ae20z_bhd"/><circle class="uwxy6_brl"/><path class="krsjgybds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocket-casts-alt-2" /></template>
<style>
.ae20z_bhd {
  cx: 26.692px;
  cy: 8.572px;
  r: 0.75px;
  fill: currentColor;
}

.gywiubbtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 8.797c8.396 8.397 8.396 22.01 0 30.406s-22.01 8.396-30.406 0s-8.396-22.01 0-30.406");
}

.jq0jyk1on {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.702 12.573c1.436 1.023 1.335 3.394-1.113 3.394c-2.043 0-2.468-1.183-2.589-1.785c-.121.602-.546 1.785-2.59 1.785c-2.447 0-2.548-2.371-1.112-3.394m4.607-1.811l-.905.637l-.905-.637");
}

.krsjgybds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.783 5.116c.518-1.018 1.628-1.527 2.708-1.353c.776.77 1.017 1.968.499 2.986");
}

.uwxy6_brl {
  cx: 21.308px;
  cy: 8.572px;
  r: 0.75px;
  fill: currentColor;
}

.wx8b-qb_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.192 14.808c5.077 5.076 5.077 13.308 0 18.384s-13.308 5.077-18.384 0s-5.077-13.308 0-18.384m4.409-9.692C18.7 4.098 17.59 3.589 16.51 3.763c-.776.77-1.017 1.968-.499 2.986");
}

</style>
