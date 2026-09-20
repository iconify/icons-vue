<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo748bccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:u-turn-right-rounded" /></template>
<style>
.yo748bccu {
  fill: currentColor;
  d: path("M6.797 19.857q-.143-.143-.143-.357V9.385q0-2.25 1.567-3.818Q9.79 4 12.04 4t3.817 1.567t1.567 3.817v4.989l1.727-1.727q.16-.16.354-.16t.354.16t.15.364t-.15.344l-2.37 2.369q-.13.13-.267.184q-.136.053-.298.053t-.298-.053t-.267-.184l-2.37-2.37q-.16-.159-.16-.353t.16-.354t.364-.15t.344.15l1.727 1.727V9.385q0-1.823-1.28-3.104T12.038 5T8.935 6.28Q7.654 7.563 7.654 9.386V19.5q0 .214-.144.357T7.155 20t-.357-.143");
}

</style>
