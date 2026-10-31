<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rciwvcoxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-like-28-filled" /></template>
<style>
.rciwvcoxx {
  fill: currentColor;
  d: path("M13.37 3.094c.3-1.163 1.58-1.916 2.76-1.45a2.5 2.5 0 0 1 .477.212c.257.141.591.368.923.713c.677.707 1.289 1.857 1.289 3.644c0 .935-.197 2.252-.382 3.294c-.065.365-.13.704-.187.99h1.5a4.25 4.25 0 0 1 4.18 5.017l-.945 5.156a6.5 6.5 0 0 1-8.11 5.096L6.43 23.454a3.75 3.75 0 0 1-2.703-2.967l-.42-2.396c-.336-1.905.846-3.619 2.41-4.434c5.009-2.61 6.966-7.892 7.653-10.563");
}

</style>
