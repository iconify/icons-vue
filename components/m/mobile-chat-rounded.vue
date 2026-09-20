<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww5-l1soe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-chat-rounded" /></template>
<style>
.ww5-l1soe {
  fill: currentColor;
  d: path("M17.23 7.923h-3.307q-1.365 0-2.279.914t-.913 2.279V18.7q0 .64.379 1.09t.942.637t1.212.06t1.2-.677l1.111-1.118h1.656q.31 0 .54.23q.229.23.229.54v.923q0 .666-.475 1.14t-1.14.475h-8.77q-.666 0-1.14-.475T6 20.386V3.615q0-.666.475-1.14T7.615 2h8.77q.666 0 1.14.475T18 3.614v3.539q0 .31-.23.54t-.54.229m2.732 8.385h-5.366l-.784.784q-.106.106-.227.128t-.227-.028t-.174-.14t-.068-.233v-5.696q0-.356.231-.585q.233-.23.576-.23h6.038q.344 0 .576.232t.232.576V15.5q0 .343-.232.576t-.576.232M12.588 6.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>
