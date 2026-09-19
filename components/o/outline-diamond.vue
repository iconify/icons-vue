<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg1yn_e7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-diamond" /></template>
<style>
.mg1yn_e7x {
  fill: currentColor;
  d: path("M19 3H5L2 9l10 12L22 9zM9.62 8l1.5-3h1.76l1.5 3zM11 10v6.68L5.44 10zm2 0h5.56L13 16.68zm6.26-2h-2.65l-1.5-3h2.65zM6.24 5h2.65l-1.5 3H4.74z");
}

</style>
