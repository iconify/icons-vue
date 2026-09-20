<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg-xkdb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:south-outline-rounded" /></template>
<style>
.yg-xkdb_v {
  fill: currentColor;
  d: path("M11.702 20.618q-.136-.052-.267-.183l-5.427-5.427q-.14-.14-.14-.344q0-.205.14-.345q.146-.146.337-.153t.332.134l4.823 4.817V3.481q0-.214.143-.357T12 2.981t.357.143t.143.357v15.617l4.798-4.798q.146-.146.357-.156q.21-.01.356.156q.141.146.141.347t-.14.342l-5.446 5.445q-.132.131-.268.184t-.298.053t-.298-.053");
}

</style>
