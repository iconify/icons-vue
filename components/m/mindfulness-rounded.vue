<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2slrxlua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mindfulness-rounded" /></template>
<style>
.x2slrxlua {
  fill: currentColor;
  d: path("M12.357 13.356q.143-.143.143-.356V8q0-.213-.144-.356t-.357-.144t-.356.144T11.5 8v5q0 .213.144.356t.357.144t.356-.144m3-1.5q.143-.143.143-.356V9q0-.213-.144-.356t-.357-.144t-.356.144T14.5 9v2.5q0 .213.144.356t.357.144t.356-.144m-6-.5Q9.5 11.213 9.5 11V9q0-.213-.144-.356T8.999 8.5t-.356.144T8.5 9v2q0 .213.144.356t.357.144t.356-.144M7.5 21q-.213 0-.356-.144T7 20.5v-3.262q-1.425-1.3-2.212-2.922T4 10.986q0-3.327 2.333-5.657T12 3q2.702 0 4.884 1.645t2.83 4.25l1.036 4.103q.1.38-.142.692q-.242.31-.646.31H18v3.385q0 .666-.475 1.14t-1.14.475H14v1.5q0 .213-.144.356T13.5 21z");
}

</style>
