<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idu8l4bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-hairdresser" /></template>
<style>
.idu8l4bsy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.544 15.596Q10.5 16.6 10.5 18q0 1.45-1.025 2.475T7 21.5q-3.5 0-3.5-3.5T7 14.5q.705 0 1.31.242l2.759-3.756l-5.173-7.042q-.089-.12-.124-.265t-.013-.292q.022-.148.099-.275t.198-.216q.059-.044.126-.075q.067-.032.139-.049t.146-.021t.146.008q.073.011.143.036t.132.063q.064.039.118.089q.055.049.098.109L12 9.719l4.896-6.663q.043-.06.098-.109q.054-.05.118-.089q.063-.038.132-.063q.07-.025.143-.036q.073-.012.146-.008q.074.003.146.021q.072.017.139.049q.067.031.126.075q.12.088.198.216q.077.127.099.275q.023.147-.013.292t-.124.265l-5.173 7.042l2.704 3.682Q16.234 14.5 17 14.5q3.5 0 3.5 3.5T17 21.5T13.5 18q0-1.703.829-2.577L12 12.253z");
}

</style>
