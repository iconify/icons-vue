<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdnkc8bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-wifi-1-bar-outline-rounded" /></template>
<style>
.jdnkc8bmq {
  fill: currentColor;
  d: path("M9.025 15.175q.625-.45 1.388-.7t1.587-.25t1.588.25t1.387.7L21.1 9.05q-1.95-1.475-4.262-2.262T12 6t-4.837.788T2.9 9.05zm2.242 3.67L2.256 9.832q-.165-.166-.239-.358t-.073-.394q0-.233.098-.438q.099-.204.295-.37q2.107-1.621 4.557-2.447T12 5t5.106.826t4.557 2.447q.196.166.295.37q.098.205.098.438q0 .202-.073.394q-.074.192-.239.358l-9.011 9.011q-.166.165-.348.239q-.183.073-.385.073t-.385-.073q-.182-.074-.348-.239");
}

</style>
