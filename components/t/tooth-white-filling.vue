<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-lhbvbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-white-filling" /></template>
<style>
.e-lhbvbaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.077q3.593-2.459 6.622-.728l.025.015q3.372 2.107 1.049 7.915q-.628 1.57-1.309 4.91q-.395 1.937-.659 2.993q-.517 2.068-2.103 2.068t-2.103-2.068l-1-4Q12.477 15 12 15t-.522.182l-1 4q-.517 2.068-2.103 2.068t-2.103-2.068q-.264-1.056-.659-2.993q-.681-3.34-1.309-4.91q-2.323-5.808 1.049-7.915l.025-.015Q8.407 1.618 12 4.077M8.25 9.5q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732T15.75 9.5t-.732-1.768T13.25 7h-2.5q-2.5 0-2.5 2.5");
}

</style>
