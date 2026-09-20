<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_5ilnbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-email-unread-outline" /></template>
<style>
.z_5ilnbrb {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h9.947q-.043.25-.053.49q-.009.24.014.51H4.308L12 11l3.573-2.333q.177.171.359.332t.382.297L12 12.116L4 6.885v10.5q0 .269.173.442t.443.173h14.769q.269 0 .442-.173t.173-.443V10.15q.287-.067.527-.158q.24-.09.473-.223v7.616q0 .69-.462 1.152T19.385 19zM4 6v12zm13.23 1.539q-.73-.731-.73-1.77T17.23 4T19 3.27t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73");
}

</style>
