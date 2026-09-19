<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z6sc1ob9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:michelinguide" /></template>
<style>
.z6sc1ob9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.53 25.961c-1.355-.783-3.973-1.602-6.546-1.961c2.573-.36 5.191-1.178 6.547-1.961a6.052 6.052 0 0 0-6.052-10.482c-1.384.8-3.46 2.72-5.073 4.819c1.018-2.452 1.646-5.221 1.646-6.824a6.052 6.052 0 0 0-12.104 0c0 1.603.628 4.372 1.646 6.824c-1.613-2.1-3.689-4.02-5.073-4.819a6.052 6.052 0 1 0-6.052 10.482c1.356.783 3.974 1.602 6.546 1.961c-2.572.36-5.19 1.178-6.546 1.961a6.052 6.052 0 0 0 6.052 10.482c1.384-.8 3.46-2.72 5.073-4.819c-1.018 2.452-1.646 5.221-1.646 6.824a6.052 6.052 0 0 0 12.104 0c0-1.603-.628-4.372-1.646-6.824c1.612 2.1 3.689 4.02 5.073 4.819a6.052 6.052 0 1 0 6.052-10.482");
}

</style>
