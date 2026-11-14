<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9o6cfb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-square" /></template>
<style>
.g9o6cfb4p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.25h7.5q2.485 0 4.243 1.757Q21.75 5.765 21.75 8.25v7.5q0 2.485-1.757 4.243q-.814.813-1.784 1.25q.041-.118.041-.243q0-2.864-1.862-4.61q-1.75-1.64-4.388-1.64t-4.388 1.64Q5.75 18.136 5.75 21q0 .125.041.243q-.97-.437-1.784-1.25Q2.25 18.235 2.25 15.75v-7.5q0-2.485 1.757-4.243Q5.765 2.25 8.25 2.25M6.929 21.615q.633.135 1.321.135h7.5q.688 0 1.321-.135q-.074-.052-.134-.12t-.102-.148t-.063-.168T16.75 21q0-4.75-4.75-4.75T7.25 21q0 .091-.022.179t-.063.168q-.042.08-.102.148t-.134.12M12 5.75q-3.75 0-3.75 3.75T12 13.25t3.75-3.75T12 5.75");
}

</style>
