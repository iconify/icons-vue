<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh7-9sbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:syrup-bottle" /></template>
<style>
.wh7-9sbxx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 6V3.5q0-1.75 1.75-1.75h4q1.75 0 1.75 1.75V6q0 .116-.035.227t-.103.206t-.16.165t-.202.109v.278q3.5 1.447 3.5 4.515V20q0 2.25-2.25 2.25h-9q-2.25 0-2.25-2.25v-8.5q0-3.068 3.5-4.515v-.278q-.11-.039-.202-.109t-.16-.165t-.103-.206T8.25 6m-1.5 9.25V20q0 .75.75.75h9q.75 0 .75-.75v-4.75zm10.5-1.5H6.75V11.5q0-2.221 3.002-3.294q.11-.039.202-.109t.159-.165t.102-.205t.035-.227v-.75h3.5v.75q0 .116.035.227q.035.11.102.205t.159.165t.202.109Q17.25 9.279 17.25 11.5z");
}

</style>
