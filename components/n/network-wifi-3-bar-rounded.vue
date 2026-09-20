<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sru1fib-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-wifi-3-bar-rounded" /></template>
<style>
.sru1fib-q {
  fill: currentColor;
  d: path("M11.267 18.844L2.256 9.833q-.165-.166-.239-.358t-.073-.394q0-.233.098-.438q.099-.204.295-.37q2.107-1.621 4.557-2.447T12 5t5.106.826t4.557 2.447q.196.166.295.37q.098.205.098.438q0 .202-.073.394q-.074.192-.239.358l-9.011 9.011q-.166.165-.348.239q-.183.073-.385.073t-.385-.073q-.182-.074-.348-.239M5.8 11.95q1.325-.95 2.9-1.487t3.3-.538t3.3.538t2.9 1.487l2.9-2.9q-1.95-1.475-4.262-2.262T12 6t-4.837.788T2.9 9.05z");
}

</style>
