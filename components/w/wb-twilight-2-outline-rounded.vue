<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m19zh486k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wb-twilight-2-outline-rounded" /></template>
<style>
.m19zh486k {
  fill: currentColor;
  d: path("M3 19.5q-.213 0-.357-.143T2.5 19t.143-.357T3 18.5h18q.214 0 .357.143T21.5 19t-.143.357T21 19.5zM7.425 14h9.15q-.575-1.35-1.81-2.175Q13.532 11 12 11t-2.766.825T7.426 14m-1.31 1q.347-2.175 2.009-3.588T12 10t3.876 1.413T17.884 15zM12 14");
}

</style>
