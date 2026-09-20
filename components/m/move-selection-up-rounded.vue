<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iai8a4zbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-up-rounded" /></template>
<style>
.iai8a4zbf {
  fill: currentColor;
  d: path("M8.577 13.077q-.671 0-1.143-.472q-.473-.472-.473-1.143V4.616q0-.672.473-1.144Q7.906 3 8.577 3h6.846q.671 0 1.143.472q.473.472.473 1.144v6.846q0 .67-.473 1.143q-.472.472-1.143.472zm-1.434 3.78q-.181-.182-.181-.434t.181-.433t.434-.182t.434.182t.181.433t-.182.434t-.433.182t-.434-.182m0 3.961q-.181-.181-.181-.433t.181-.434t.434-.182q.252 0 .434.182t.181.434t-.182.433t-.433.182t-.434-.182m4.423 0q-.182-.182-.182-.434q0-.251.182-.433t.434-.182t.434.182t.182.434q0 .251-.182.433T12 21t-.434-.182m4.424 0q-.182-.182-.182-.434q0-.251.182-.433t.433-.182t.434.182t.181.434q0 .251-.181.433t-.434.182t-.433-.182m0-3.961q-.182-.182-.182-.434t.181-.433t.434-.182t.434.181t.181.434t-.181.434t-.434.181t-.433-.181");
}

</style>
