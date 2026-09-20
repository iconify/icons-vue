<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt_6vibsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-remote-outline-sharp" /></template>
<style>
.mt_6vibsp {
  fill: currentColor;
  d: path("M9 21h6v-6.404q-.529.648-1.31 1.026Q12.907 16 12 16t-1.69-.378q-.78-.378-1.31-1.026zm5.125-6.875Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875M9 9.404q.529-.648 1.31-1.026Q11.093 8 12 8t1.69.378q.781.378 1.31 1.026V3H9zM8 22V2h8v20zm3.11-9.11q-.36-.361-.36-.89t.36-.89q.361-.36.89-.36t.89.36q.36.361.36.89t-.36.89q-.361.36-.89.36t-.89-.36m1.41-7.37q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21M12 8");
}

</style>
