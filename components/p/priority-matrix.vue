<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zonr3lbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:priority-matrix" /></template>
<style>
.zonr3lbet {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h-1.75q-1.398 0-2.386.989q-.989.988-.989 2.386v1.75q0 1.398.989 2.386q.988.989 2.386.989h1.75q3.375 0 3.375-3.375v-1.75q0-1.398-.989-2.386q-.988-.989-2.386-.989m9.25 0h1.75q1.398 0 2.386.989q.989.988.989 2.386v1.75q0 3.375-3.375 3.375h-1.75q-3.375 0-3.375-3.375v-1.75q0-1.398.989-2.386q.988-.989 2.386-.989m-9.25 11h-1.75q-1.398 0-2.386.989q-.989.988-.989 2.386v1.75q0 1.398.989 2.386q.988.989 2.386.989h1.75q3.375 0 3.375-3.375v-1.75q0-3.375-3.375-3.375m9.25 0h1.75q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375h-1.75q-3.375 0-3.375-3.375v-1.75q0-3.375 3.375-3.375");
}

</style>
