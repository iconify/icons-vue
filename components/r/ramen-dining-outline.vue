<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-9_c1b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ramen-dining-outline" /></template>
<style>
.h-9_c1b_a {
  fill: currentColor;
  d: path("M9.885 20h4.192v-1.138l.558-.193q1.913-.592 3.253-1.918T19.727 14H4.273q.5 1.425 1.818 2.751q1.317 1.326 3.236 1.918l.558.193zm-1 1v-1.442q-2.387-.743-3.972-2.577Q3.327 15.146 3 13h2V4.75L21 3v.904L10.423 5.069v2.104H21v.885H10.423V13H21q-.288 2.146-1.912 3.98q-1.625 1.836-4.011 2.578V21zM8.154 7.173h1.385V5.161l-1.385.145zm-2.27 0H7.27v-1.77l-1.384.158zM8.155 13H9.54V8.058H8.153zm-2.27 0H7.27V8.058H5.884zM12 14");
}

</style>
