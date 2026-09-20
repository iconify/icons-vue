<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-9jifbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-4-outline-rounded" /></template>
<style>
.b-9jifbnl {
  fill: currentColor;
  d: path("M11.277 15.492q.6.293 1.243.053t.836-.903q.473-1.58.913-3.16q.44-1.578.879-3.172q.1-.335-.216-.484t-.534.143q-.938 1.366-1.888 2.7t-1.875 2.697q-.39.557-.173 1.196t.815.93M5.106 19q-.275 0-.51-.132q-.234-.131-.394-.395q-.496-.856-.846-1.964T3.006 14q0-2.1.872-3.892q.872-1.793 2.374-3.039q1.31-1.098 2.932-1.63q1.622-.533 3.312-.42q.188.025.312.177q.123.152.092.36t-.179.335t-.338.128q-1.471-.083-2.854.383Q8.146 6.867 6.98 7.8q-1.35 1.125-2.163 2.725T4.006 14q0 1.05.287 2.075T5.106 18H18.9q.575-.95.838-1.963T20 14q0-1.552-.553-2.929t-1.541-2.446q-.147-.177-.139-.37t.167-.345q.16-.154.374-.157q.213-.003.376.191q1.122 1.222 1.719 2.786T21 14q0 1.21-.277 2.315t-.92 2.235q-.095.206-.352.328T18.9 19zm6.817-4.871");
}

</style>
