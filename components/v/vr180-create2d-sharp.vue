<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijniofbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vr180-create2d-sharp" /></template>
<style>
.ijniofbjy {
  fill: currentColor;
  d: path("M10.385 21V10.385H21V21zm2.5-2.192h6.23l-1.915-2.5l-1.7 2.25l-1.2-1.65zM8 16.712q-2.252-.656-3.626-2.507T3 10q0-2.931 2.034-4.966Q7.07 3 10 3q2.354 0 4.205 1.374T16.712 8H8z");
}

</style>
