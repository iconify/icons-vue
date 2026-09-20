<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x88ho-bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-card-outline-rounded" /></template>
<style>
.x88ho-bot {
  fill: currentColor;
  d: path("M13 21q-.69 0-1.153-.462t-.462-1.153V15q0-.69.462-1.153T13 13.385h7.385q.69 0 1.153.462T22 15v4.385q0 .69-.462 1.152T20.385 21zm0-1h7.385q.269 0 .442-.173t.173-.442v-2.193h-8.615v2.193q0 .269.173.442T13 20m-.615-3.808H21V15q0-.27-.173-.442q-.173-.173-.442-.173H13q-.27 0-.442.173q-.173.173-.173.442zM8.317 18.82q-1.59-1.496-2.454-3.516Q5 13.283 5 11.1V6.817q0-.51.295-.923t.755-.6l5.596-2.08q.162-.056.354-.056t.354.055l5.596 2.081q.46.187.755.6t.295.923V10.5q0 .214-.143.357T18.5 11t-.357-.143T18 10.5V6.798q0-.192-.106-.346q-.105-.154-.298-.23l-5.384-2q-.096-.04-.212-.04t-.212.04l-5.384 2q-.193.076-.298.23Q6 6.606 6 6.798V11.1q0 2.025.813 3.863T9 18.1q.146.14.159.344t-.128.35t-.354.156t-.36-.13");
}

</style>
