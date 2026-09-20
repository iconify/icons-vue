<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6v_55bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-speaker-outline-sharp" /></template>
<style>
.a6v_55bhp {
  fill: currentColor;
  d: path("M4 18V9zm-1 1V5h1.616l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3H21v4H4v9h4.616v1zm12.75 1.539l-2.192-2.155H11v-2.788h2.558l2.192-2.134zm2 1.207v-1.069q1.377-.235 2.285-1.265q.907-1.031.907-2.431t-.907-2.431t-2.285-1.265v-1.05q1.804.234 2.998 1.577T21.942 17q0 1.827-1.194 3.17t-2.998 1.576m0-2.946v-3.62q.579.199.934.69q.354.49.354 1.13q0 .621-.354 1.112q-.355.49-.934.688");
}

</style>
