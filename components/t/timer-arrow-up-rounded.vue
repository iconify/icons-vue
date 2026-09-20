<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wplg4qb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-arrow-up-rounded" /></template>
<style>
.wplg4qb_y {
  fill: currentColor;
  d: path("M4.207 17.13q-1.86-1.87-1.86-4.534t1.86-4.533t4.524-1.87q1.185 0 2.248.402q1.063.403 1.898 1.128l.62-.62q.14-.14.34-.133t.348.153q.14.14.14.335t-.14.334l-.6.62q.725.834 1.137 1.9t.413 2.284q0 2.663-1.87 4.534T8.73 19t-4.524-1.87m3.1-12.36q-.213 0-.356-.144t-.143-.357t.143-.357t.357-.143h2.884q.214 0 .357.143t.143.357t-.143.357t-.357.143zm1.78 7.99q.144-.143.144-.356V9.596q0-.213-.143-.356t-.357-.144t-.357.144t-.143.356v2.808q0 .213.143.357t.357.143t.357-.143m9.797-5.845l-1.37 1.369q-.16.16-.353.16t-.354-.16t-.16-.354t.16-.354l2.011-2.011q.243-.243.566-.243t.565.243l2.012 2.011q.16.165.16.357t-.166.35q-.166.16-.357.163t-.351-.162L19.884 6.92V18.5q0 .214-.143.357t-.356.143t-.357-.143t-.143-.357z");
}

</style>
