<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powei489y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-elevator" /></template>
<style>
.powei489y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 17.125V6.875q0-2.123 1.501-3.624T8.875 1.75m4.716 4.281q-.659-.66-1.591-.66t-1.591.66L9.22 7.22q-.977.977-.449 2.253q.529 1.277 1.911 1.277h2.636q1.382 0 1.911-1.277q.528-1.276-.449-2.253zm-2.909 7.219q-1.382 0-1.911 1.277q-.528 1.276.449 2.253l1.189 1.189q.659.66 1.591.66t1.591-.66l1.189-1.189q.977-.977.449-2.253q-.529-1.277-1.911-1.277z");
}

</style>
