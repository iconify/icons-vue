<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbkr6ibiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumbs-up-double" /></template>
<style>
.kbkr6ibiv {
  fill: currentColor;
  d: path("m17.842 16.192l.525-1.228q.175-.375.25-.763t.075-.812V13q0-1.65-1.175-2.825T14.692 9h-1.457q.106-.8-.048-1.506q-.154-.705-.556-1.298L15.808 3l.396.396q.273.273.381.624q.11.351.053.73l-.407 2.827h4.153q.672 0 1.144.472T22 9.192v.364q0 .161-.038.323q-.037.162-.093.304l-2.21 5.188q-.153.377-.5.6q-.346.221-.753.221zM2 20v-8.615h1.462V20zm3.385 0v-8.538l4.634-4.654l.396.396q.274.273.392.634t.062.739l-.408 2.808h4.231q.671 0 1.143.472q.473.472.473 1.143v.389q0 .161-.038.31t-.093.31l-2.152 5.022q-.192.454-.596.711q-.404.258-.888.258z");
}

</style>
