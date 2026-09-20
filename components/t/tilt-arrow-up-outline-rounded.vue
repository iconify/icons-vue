<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-5pjccqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tilt-arrow-up-outline-rounded" /></template>
<style>
.f-5pjccqx {
  fill: currentColor;
  d: path("M5.02 20q-.778 0-1.262-.593q-.485-.594-.304-1.37l2.869-12.77q.13-.546.575-.906Q7.342 4 7.908 4h8.165q.566 0 1.01.36q.444.361.575.907l2.888 12.77q.181.777-.304 1.37q-.484.593-1.261.593zM5 19h13.962q.307 0 .49-.23q.183-.232.106-.52L16.669 5.48q-.038-.21-.221-.345Q16.266 5 16.054 5H7.908q-.212 0-.395.135q-.182.134-.22.346L4.402 18.25q-.076.289.107.52q.182.23.49.23m6.48-8.079v4.195q0 .213.144.356q.143.144.357.144t.357-.144t.143-.356V10.92l1.765 1.766q.14.14.341.15q.202.01.367-.156q.16-.16.16-.354t-.16-.354l-2.408-2.407q-.242-.243-.565-.243t-.565.243l-2.37 2.369q-.14.14-.15.341t.15.366q.166.166.357.166t.357-.166zM18.963 19H4.846h14.27z");
}

</style>
