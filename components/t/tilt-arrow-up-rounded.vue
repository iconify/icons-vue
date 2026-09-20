<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he2kv6gqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tilt-arrow-up-rounded" /></template>
<style>
.he2kv6gqu {
  fill: currentColor;
  d: path("M5.02 20q-.778 0-1.262-.593q-.485-.594-.304-1.37l2.869-12.77q.13-.546.575-.906Q7.342 4 7.908 4h8.165q.566 0 1.01.36q.444.361.575.907l2.888 12.77q.181.777-.304 1.37q-.484.593-1.261.593zm6.46-9.079v4.195q0 .213.144.356q.143.144.357.144t.357-.144t.143-.356V10.92l1.765 1.766q.14.14.341.15q.202.01.367-.156q.16-.16.16-.354t-.16-.354l-2.408-2.407q-.242-.243-.565-.243t-.565.243l-2.37 2.369q-.14.14-.15.341t.15.366q.166.166.357.166t.357-.166z");
}

</style>
