<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-fkhhiaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mass-weight" /></template>
<style>
.p-fkhhiaj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3Q9 3.75 9 5.25q0 2.598 2.25 2.946v.054H9.028q-2.607 0-3.266 2.523l-1.63 6.25q-.418 1.603.595 2.915t2.671 1.312h9.204q1.658 0 2.671-1.312t.595-2.915l-1.63-6.25q-.659-2.523-3.266-2.523H12.75v-.054Q15 7.848 15 5.25q0-3-3-3q-1.5 0-2.25.75");
}

</style>
