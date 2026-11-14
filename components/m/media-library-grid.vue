<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp1s7qk6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:media-library-grid" /></template>
<style>
.vp1s7qk6y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.25h-2.25q-1.398 0-2.386.989q-.989.988-.989 2.386v2.25q0 1.398.989 2.386q.988.989 2.386.989h2.25q3.375 0 3.375-3.375v-2.25q0-1.398-.989-2.386q-.988-.989-2.386-.989m8.25 0h2.25q1.398 0 2.386.989q.989.988.989 2.386v2.25q0 3.375-3.375 3.375h-2.25q-3.375 0-3.375-3.375v-2.25q0-1.398.989-2.386q.988-.989 2.386-.989m-8.25 10.5h-2.25q-1.398 0-2.386.989q-.989.988-.989 2.386v2.25q0 1.398.989 2.386q.988.989 2.386.989h2.25q3.375 0 3.375-3.375v-2.25q0-3.375-3.375-3.375m9.055 1.469l1.544.827q1.32.706 1.32 2.204t-1.32 2.204l-1.544.827q-1.249.669-2.465-.059t-1.215-2.145v-1.654q0-1.417 1.215-2.145t2.465-.059");
}

</style>
