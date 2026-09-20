<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8e106_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker" /></template>
<style>
.ar8e106_l {
  fill: currentColor;
  d: path("M16.385 21h-8.77q-.666 0-1.14-.475T6 19.386V4.615q0-.666.475-1.14T7.615 3h8.77q.666 0 1.14.475T18 4.615v14.77q0 .666-.475 1.14t-1.14.475M13.142 8.14q.473-.476.473-1.144t-.476-1.14t-1.143-.472t-1.14.476t-.472 1.143t.475 1.14t1.144.472t1.14-.475m1.306 9.31q1.012-1.012 1.012-2.45t-1.012-2.45T12 11.538T9.55 12.55T8.538 15t1.012 2.45T12 18.462t2.45-1.012m-4.19-.712q-.721-.723-.721-1.74q0-1.015.723-1.737q.724-.723 1.74-.723q1.015 0 1.738.724q.722.723.722 1.74q0 1.015-.724 1.737q-.723.722-1.74.722q-1.015 0-1.737-.723");
}

</style>
