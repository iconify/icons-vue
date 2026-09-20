<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stuyoabex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-camera-sharp" /></template>
<style>
.stuyoabex {
  fill: currentColor;
  d: path("M3 20V6h4.573l1.85-2h5.154l1.85 2H21v14zm6.692-3.654l.708-.707l-2.088-2.089h7.377L13.6 15.639l.708.707l3.308-3.307l-3.308-3.308l-.708.708l2.1 2.111H8.3l2.1-2.111l-.708-.708l-3.308 3.308z");
}

</style>
