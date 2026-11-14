<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo6pw_uni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:massage-gun" /></template>
<style>
.mo6pw_uni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 3.75h-5.5q-1.657 0-2.828 1.172Q1.75 6.093 1.75 7.75q0 4 4 4h1v7.75q0 2.75 2.75 2.75h1q2.75 0 2.75-2.75v-8.275q.441-.259.828-.647q.897-.897 1.108-2.078h1.113Q16.65 11 19.5 11q3.25 0 3.25-3.25T19.5 4.5q-2.85 0-3.201 2.5h-1.113q-.211-1.181-1.108-2.078Q12.907 3.75 11.25 3.75m-3 15.75v-7.75h3q.256 0 .5-.028V19.5q0 1.25-1.25 1.25h-1q-1.25 0-1.25-1.25");
}

</style>
