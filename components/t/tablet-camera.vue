<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd95m6brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-camera" /></template>
<style>
.gd95m6brf {
  fill: currentColor;
  d: path("M18 20V6H6v14H3q-.825 0-1.412-.587T1 18V6q0-.825.588-1.412T3 4h18q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20zm-9 2q-.625 0-1.062-.437T7.5 20.5v-4q0-.625.438-1.062T9 15h1l1-1h2l1 1h1q.625 0 1.063.438T16.5 16.5v4q0 .625-.437 1.063T15 22zm4.238-2.262q.512-.513.512-1.238t-.513-1.237T12 16.75t-1.237.513t-.513 1.237t.513 1.238T12 20.25t1.238-.513");
}

</style>
