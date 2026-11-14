<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9rrhabhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-compare-groceries" /></template>
<style>
.v9rrhabhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.352 20.5H6.41q-.149 0-.295-.025q-.147-.025-.287-.075t-.27-.122t-.246-.165t-.214-.205t-.177-.238t-.134-.265t-.087-.283l-1.739-8q-.021-.095-.031-.193q-.01-.097-.009-.195q.001-.097.013-.194q.011-.097.034-.192q.022-.096.055-.188t.076-.179t.096-.171q.052-.082.113-.158t.131-.145t.146-.129q.077-.061.16-.113q.083-.051.171-.094q.088-.042.18-.074t.188-.054t.192-.032T4.671 9h14.658q.098 0 .195.011t.192.032q.096.022.188.054t.18.074t.171.094t.16.113t.146.129t.131.145q.061.076.113.158q.053.083.096.171q.043.087.076.179t.055.188q.023.095.034.192t.013.194q.001.098-.009.195q-.01.098-.031.193l-.238 1.095M7 9l3-5.5M17 9l-3-5.5m1 12.75h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
