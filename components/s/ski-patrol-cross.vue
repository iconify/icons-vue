<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd-0eobzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ski-patrol-cross" /></template>
<style>
.vd-0eobzb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.875 2.25h-5.75q-2.848 0-4.861 2.014T2.25 9.125v5.75q0 2.848 2.014 4.861t4.861 2.014h5.75q2.848 0 4.861-2.014t2.014-4.861v-5.75q0-2.848-2.014-4.861T14.875 2.25m-3.625 3.5h1.5Q15 5.75 15 8v.25q0 .75.75.75H16q2.25 0 2.25 2.25v1.5Q18.25 15 16 15h-.25q-.75 0-.75.75V16q0 2.25-2.25 2.25h-1.5Q9 18.25 9 16v-.25Q9 15 8.25 15H8q-2.25 0-2.25-2.25v-1.5Q5.75 9 8 9h.25Q9 9 9 8.25V8q0-2.25 2.25-2.25");
}

</style>
