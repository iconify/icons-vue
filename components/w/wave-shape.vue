<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6z58uw-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wave-shape" /></template>
<style>
.k6z58uw-h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.295 11.744Q3.975 7.125 6 7.125t3.705 4.619q1.32 3.631 2.295 3.631t2.295-3.631Q15.975 7.125 18 7.125t3.705 4.619q.025.069.036.142q.012.073.008.147q-.003.074-.021.145q-.017.072-.048.139q-.032.067-.075.127q-.044.059-.098.109t-.118.088q-.063.039-.133.064q-.069.025-.142.036q-.073.012-.147.008q-.074-.003-.145-.021q-.072-.017-.139-.048q-.067-.032-.127-.075q-.059-.044-.109-.098t-.088-.118q-.039-.063-.064-.133Q18.975 8.625 18 8.625t-2.295 3.631q-1.68 4.619-3.705 4.619t-3.705-4.619Q6.975 8.625 6 8.625t-2.295 3.631q-.051.141-.152.251t-.236.173t-.284.069t-.289-.044q-.07-.025-.133-.064q-.063-.038-.118-.088t-.098-.109t-.075-.127t-.048-.139q-.018-.071-.021-.145t.008-.147t.036-.142");
}

</style>
