<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aeg-my7ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-32-light" /></template>
<style>
.aeg-my7ru {
  fill: currentColor;
  d: path("M16.941 2.806a2.75 2.75 0 0 1 3.89 0l1.576 1.576c.27.27.282.675.092.962A3 3 0 0 0 26.655 9.5l.113-.063a.77.77 0 0 1 .742.064l.107.09l1.577 1.577a2.75 2.75 0 0 1 0 3.89L15.058 29.194a2.75 2.75 0 0 1-3.889 0l-1.577-1.577a.76.76 0 0 1-.091-.962l.111-.182a3 3 0 0 0-4.269-3.974a.764.764 0 0 1-.961-.092l-1.576-1.576a2.75 2.75 0 0 1 0-3.89zm3.183.707a1.75 1.75 0 0 0-2.476 0l-4.213 4.213l1.86 1.86a.5.5 0 0 1-.707.707l-1.86-1.86l-9.215 9.215a1.75 1.75 0 0 0 0 2.476l1.441 1.442A4 4 0 0 1 11 25a4 4 0 0 1-.566 2.044l1.442 1.442a1.75 1.75 0 0 0 2.475 0l9.215-9.215l-1.857-1.858a.5.5 0 0 1 .707-.707l1.857 1.857l4.214-4.212a1.75 1.75 0 0 0 0-2.476l-1.442-1.442A4 4 0 0 1 25 11a4 4 0 0 1-3.435-6.046zm-3.415 8.194a.5.5 0 0 1 .707 0l2.879 2.879a.5.5 0 0 1-.707.707l-2.879-2.879a.5.5 0 0 1 0-.707");
}

</style>
