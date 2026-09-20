<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kooh92b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tilt-arrow-up-outline" /></template>
<style>
.kooh92b5d {
  fill: currentColor;
  d: path("M5.02 20q-.778 0-1.262-.593q-.485-.594-.304-1.37l2.869-12.77q.13-.546.575-.906Q7.342 4 7.908 4h8.165q.566 0 1.01.36q.444.361.575.907l2.888 12.77q.181.777-.304 1.37q-.484.593-1.261.593zM5 19h13.962q.307 0 .49-.23q.183-.232.106-.52L16.669 5.48q-.038-.21-.221-.345Q16.266 5 16.054 5H7.908q-.212 0-.395.135q-.182.134-.22.346L4.402 18.25q-.076.289.107.52q.182.23.49.23m6.48-8.079v4.695h1V10.92l2.12 2.114l.708-.708L11.98 9l-3.289 3.289l.708.713zM18.963 19H4.846h14.27z");
}

</style>
