<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-dpir8tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:package-open" /></template>
<style>
.w-dpir8tu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.84 11.644q-.09.167-.09.356v7q0 .116.035.227t.103.206t.16.165q.093.071.202.109l8.5 3q.122.043.25.043t.25-.043l8.5-3q.109-.038.202-.109q.093-.07.16-.165t.103-.206q.035-.111.035-.227v-7.001q0-.148-.056-.285l-.002-.004q-.014-.034-.032-.066l-3.5-6.5q-.034-.063-.08-.119t-.102-.103q-.055-.046-.119-.08q-.064-.035-.133-.057t-.141-.03t-.144-.003t-.142.025t-.134.052L12 7.161L7.335 4.829q-.064-.032-.134-.052t-.142-.025t-.144.003t-.141.03t-.133.057q-.064.034-.119.08q-.056.047-.102.103t-.08.119zm1.715-.021l2.76-5.127l4.35 2.175q.078.039.163.059t.172.02t.172-.02t.163-.059l4.35-2.175l2.76 5.127L12 14.689z");
}

</style>
