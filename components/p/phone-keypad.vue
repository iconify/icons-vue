<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um6fzac1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-keypad" /></template>
<style>
.um6fzac1t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75q-2 0-2 2t2 2t2-2t-2-2m4 2q0-2 2-2t2 2t-2 2t-2-2m8-2q-2 0-2 2t2 2t2-2t-2-2M4 9.25q0-2 2-2t2 2t-2 2t-2-2m8-2q-2 0-2 2t2 2t2-2t-2-2m4 2q0-2 2-2t2 2t-2 2t-2-2m-10 3.5q-2 0-2 2t2 2t2-2t-2-2m4 2q0-2 2-2t2 2t-2 2t-2-2m8-2q-2 0-2 2t2 2t2-2t-2-2m-8 7.5q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
