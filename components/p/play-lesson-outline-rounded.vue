<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5i46abqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-lesson-outline-rounded" /></template>
<style>
.h5i46abqv {
  fill: currentColor;
  d: path("M5.616 21q-.691 0-1.153-.462T4 19.385V4.615q0-.69.463-1.152T5.616 3h10.769q.69 0 1.153.463T18 4.616v6.519q0 .213-.143.356t-.357.144t-.357-.144t-.143-.356v-6.52q0-.23-.192-.423T16.384 4H11.5v5.49q0 .237-.202.358t-.413-.01L9.5 9l-1.384.839q-.212.13-.414.009T7.5 9.49V4H5.616q-.231 0-.424.192T5 4.615v14.77q0 .23.192.423t.423.192h5.347q.213 0 .356.143t.144.357t-.144.357t-.356.143zm9.049-.472Q13.5 19.364 13.5 17.692q0-1.67 1.165-2.835q1.164-1.165 2.835-1.165t2.836 1.165t1.164 2.835t-1.164 2.836t-2.836 1.164t-2.835-1.164m2.61-1.407l1.627-1.138q.173-.131.173-.33q0-.197-.173-.328l-1.627-1.138q-.211-.131-.426-.022q-.214.108-.214.35v2.277q0 .243.214.351t.426-.022M7.558 4h4zM5 20V4v5.851V9v.851V4z");
}

</style>
