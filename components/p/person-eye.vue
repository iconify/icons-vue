<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di3rjnbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-eye" /></template>
<style>
.di3rjnbbj {
  fill: currentColor;
  d: path("M7.377 10.508Q6.5 9.63 6.5 8.385t.877-2.123T9.5 5.385t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877M16.135 22q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.382-.94t3.383.94T22 18.538q-.933 1.581-2.483 2.521q-1.55.941-3.382.941m1.255-2.206q.514-.513.514-1.256t-.514-1.255t-1.256-.514q-.742 0-1.255.514q-.513.513-.513 1.255t.513 1.256t1.256.514t1.255-.514m-1.962-.549q-.294-.293-.294-.707t.294-.706q.293-.294.706-.294q.414 0 .707.294t.293.706t-.293.707t-.707.293t-.706-.293m-7.886-.63H3V16.97q0-.625.36-1.161q.361-.537.97-.835q1.455-.698 2.853-1.028t2.817-.33q.623 0 1.191.067t1.115.174Q10.781 14.72 9.521 16t-1.979 2.616");
}

</style>
