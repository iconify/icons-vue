<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecrltkkcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-wifi-rounded" /></template>
<style>
.ecrltkkcb {
  fill: currentColor;
  d: path("M4.35 10.5q1.675-1.2 3.625-1.85T12 8t4.025.65t3.625 1.85l1.45-1.45q-1.975-1.5-4.3-2.275T12 6t-4.8.775T2.9 9.05zm6.917 8.344L2.256 9.833q-.165-.166-.239-.358t-.073-.394q0-.233.098-.438q.099-.204.295-.37q2.107-1.621 4.557-2.447T12 5t5.106.826t4.557 2.447q.196.166.295.37q.098.205.098.438q0 .202-.073.394q-.074.192-.239.358l-9.011 9.011q-.166.165-.348.239q-.183.073-.385.073t-.385-.073q-.182-.074-.348-.239");
}

</style>
