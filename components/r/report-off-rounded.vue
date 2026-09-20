<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2-hmwtue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:report-off-rounded" /></template>
<style>
.w2-hmwtue {
  fill: currentColor;
  d: path("M9.344 20q-.323 0-.628-.134q-.304-.133-.522-.35L4.48 15.794q-.217-.217-.348-.522T4 14.644v-5.3q0-.323.13-.628q.132-.305.349-.522L5.623 7.05L3.216 4.63q-.141-.14-.154-.34t.154-.367q.159-.16.353-.16t.354.16l16.154 16.154q.14.14.15.344t-.15.363t-.354.16t-.354-.16l-2.419-2.418l-1.138 1.144q-.218.223-.526.356q-.307.134-.636.134zM12 16.423q.252 0 .434-.182t.182-.433t-.182-.434t-.434-.182t-.434.182t-.182.434t.182.433t.434.182m6.517-.711L12.5 9.694v-1.81q0-.213-.143-.356T12 7.385t-.357.143t-.143.357v.81L8.283 5.476q-.217-.223-.215-.549t.22-.543q.193-.193.426-.289T9.219 4h5.437q.323 0 .628.13q.305.132.522.349l3.715 3.715q.218.217.348.522q.131.305.131.628v5.477q0 .235-.087.464q-.086.229-.24.402q-.217.261-.565.261q-.349 0-.59-.237");
}

</style>
