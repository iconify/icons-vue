<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsjhgfbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:u-turn-left-outline-rounded" /></template>
<style>
.dsjhgfbge {
  fill: currentColor;
  d: path("M6.99 15.907q-.136-.053-.267-.184l-2.37-2.37q-.14-.14-.15-.343t.15-.364t.355-.16t.354.16l1.727 1.727V9.385q0-2.25 1.567-3.818T12.173 4t3.818 1.567t1.567 3.817V19.5q0 .214-.144.357t-.356.143t-.357-.143t-.143-.357V9.385q0-1.823-1.281-3.104T12.173 5T9.069 6.28T7.79 9.386v4.988l1.727-1.727q.14-.14.344-.15t.363.15t.16.354t-.16.354l-2.37 2.369q-.13.13-.266.184q-.137.053-.298.053t-.298-.053");
}

</style>
