<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0i-jvb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:maple-leaf-sharp" /></template>
<style>
.i0i-jvb7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.27 3.29l1.46 2.92l.27.54l.54-.27l1.42-.71l.54-.27l-.09.59l-.57 3.82l-.09.59l.48-.36l2.04-1.53l.48-.36l.51.31l1.48.88l.51.31l-.27.54l-.96 1.92l-.27.54l.37.47l.26.31l.37.47l-.54.27l-3.92 1.96l-.54.27l.16.58l.18.59l.16.58l-.58-.14l-3.09-.72l-.58-.14l-.58.14l-3.09.72l-.58.14l.16-.58l.18-.59l.16-.58l-.54-.27l-3.92-1.96l-.54-.27l.37-.47l.26-.31l.37-.47l-.27-.54l-.96-1.92l-.27-.54l.51-.31l1.48-.88l.51-.31l.48.36l2.04 1.53l.48.36l-.09-.59l-.57-3.82l-.09-.59l.54.27l1.42.71l.54.27l.27-.54l1.46-2.92l.27-.54zM12 8.5v8.75m0 0v4");
}

</style>
