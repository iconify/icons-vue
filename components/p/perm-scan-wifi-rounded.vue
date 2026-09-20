<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdfgdg_5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-scan-wifi-rounded" /></template>
<style>
.xdfgdg_5l {
  fill: currentColor;
  d: path("M11.267 18.844L2.256 9.833q-.165-.166-.239-.358t-.073-.394q0-.233.098-.438q.099-.204.295-.37q2.107-1.621 4.557-2.447T12 5t5.106.826t4.557 2.447q.196.166.295.37q.098.205.098.438q0 .202-.073.394q-.074.192-.239.358l-9.011 9.011q-.166.165-.348.239q-.183.073-.385.073t-.385-.073q-.182-.074-.348-.239M11.5 14.5q0 .214.143.357T12 15t.357-.143t.143-.357v-4q0-.213-.143-.357T12 10t-.357.143t-.143.357zm.934-5.874q.182-.182.182-.434t-.182-.433T12 7.577t-.434.182t-.182.433t.182.434t.434.182t.434-.182");
}

</style>
