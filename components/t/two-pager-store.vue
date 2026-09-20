<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voyibw7cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:two-pager-store" /></template>
<style>
.voyibw7cg {
  fill: currentColor;
  d: path("M15.5 22q-.625 0-1.062-.437T14 20.5V19h8v1.5q0 .625-.437 1.063T20.5 22zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v5h-2V6h-7v5q-.825 0-1.412.588T11 13v7zm10.575-2q-.7 0-1.125-.55t-.3-1.25l.4-2q.125-.525.525-.862T15 13h6q.525 0 .925.337t.525.863l.4 2q.125.7-.3 1.25t-1.125.55zM5 16h5v-2H5zm0-3h5v-2H5zm0-3h5V8H5zm9 0V8h5v2z");
}

</style>
