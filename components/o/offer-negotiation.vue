<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qowsems_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:offer-negotiation" /></template>
<style>
.qowsems_z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2.25H4q-2.25 0-2.25 2.25v4q0 2.25 2.25 2.25h.25V12q0 .149.057.287t.163.243q.105.106.243.163T5 12.75t.287-.057t.243-.163l1.781-1.78H9q2.25 0 2.25-2.25v-4q0-2.25-2.25-2.25m6 0h5q2.25 0 2.25 2.25v4q0 2.25-2.25 2.25h-.25V12q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.149 0-.287-.057t-.243-.163l-1.781-1.78H15q-2.25 0-2.25-2.25v-4q0-2.25 2.25-2.25M8.818 13.818Q7.5 15.136 7.5 17t1.318 3.182T12 21.5t3.182-1.318T16.5 17t-1.318-3.182T12 12.5t-3.182 1.318");
}

</style>
