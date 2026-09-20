<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sanod7jvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-chat-read-rounded" /></template>
<style>
.sanod7jvb {
  fill: currentColor;
  d: path("m17.35 17.175l3.55-3.55q.3-.3.7-.288t.7.313q.275.3.288.7t-.288.7l-4.25 4.25q-.3.3-.7.3t-.7-.3l-2.125-2.15q-.275-.275-.287-.687t.287-.713q.275-.275.7-.275t.7.275zM6 18l-2.3 2.3q-.475.475-1.088.213T2 19.575V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v6q0 .425-.288.713T21 11h-7q-.825 0-1.412.588T12 13v4q0 .425-.288.713T11 18z");
}

</style>
