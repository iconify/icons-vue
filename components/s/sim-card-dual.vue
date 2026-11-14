<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7zui9o7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sim-card-dual" /></template>
<style>
.w7zui9o7q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.311 4.75L12.53 1.97q-.105-.106-.243-.163T12 1.75H6q-1.139 0-1.945.805q-.805.806-.805 1.945v12q0 2.75 2.75 2.75h1.25v.25q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75v-10q0-.149-.057-.287t-.163-.243l-4-4q-.105-.106-.243-.163T16 4.75zm-2.122 0H10q-2.75 0-2.75 2.75v10.25H6q-1.25 0-1.25-1.25v-12q0-1.25 1.25-1.25h5.689zm-.439 6h2.5q2.5 0 2.5 2.5v3q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-3q0-2.5 2.5-2.5");
}

</style>
