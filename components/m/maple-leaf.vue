<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkhb9i-_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:maple-leaf" /></template>
<style>
.kkhb9i-_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.27 3.29l1.46 2.92q.27.54.81.27l1.42-.71q.54-.27.45.32l-.57 3.82q-.09.59.39.23l2.04-1.53q.48-.36.99-.05l1.48.88q.51.31.24.85l-.96 1.92q-.27.54.1 1.01l.26.31q.37.47-.17.74l-3.92 1.96q-.54.27-.38.85l.18.59q.16.58-.42.44l-3.09-.72q-.58-.14-1.16 0l-3.09.72q-.58.14-.42-.44l.18-.59q.16-.58-.38-.85l-3.92-1.96q-.54-.27-.17-.74l.26-.31q.37-.47.1-1.01l-.96-1.92q-.27-.54.24-.85l1.48-.88q.51-.31.99.05l2.04 1.53q.48.36.39-.23l-.57-3.82q-.09-.59.45-.32l1.42.71q.54.27.81-.27l1.46-2.92q.27-.54.54 0M12 8.5v8.75m0 0v4");
}

</style>
