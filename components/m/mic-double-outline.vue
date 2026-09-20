<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtuylnc1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-double-outline" /></template>
<style>
.wtuylnc1b {
  fill: currentColor;
  d: path("M7.73 20.5v-3.517q-2.35-.216-3.924-1.922T2.23 11h1q0 2.075 1.462 3.538T8.231 16q.202 0 .394-.01T9 15.938q.171.23.364.447q.192.216.386.418q-.25.056-.497.103t-.522.078V20.5zm-.114-7.608q-.614-.2-1-.704q-.385-.505-.385-1.188V5q0-.846.577-1.423T8.23 3t1.423.577T10.23 5v3.616H7.385V11q0 .506.057.974t.174.918m6.73-.469q-.577-.577-.577-1.423V5q0-.846.577-1.423T15.77 3t1.423.577T17.77 5v6q0 .846-.577 1.423q-.576.577-1.423.577t-1.423-.577m.923 8.077v-3.517q-2.35-.216-3.925-1.922T9.77 11h1q0 2.075 1.463 3.537T15.769 16t3.538-1.463T20.769 11h1q0 2.356-1.575 4.061t-3.925 1.922V20.5zm1.213-8.787q.287-.288.287-.713V5q0-.425-.287-.712T15.769 4t-.712.287t-.288.713v6q0 .425.288.713t.712.287t.713-.288M15.769 8");
}

</style>
