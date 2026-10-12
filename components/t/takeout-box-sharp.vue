<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro9ouknln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:takeout-box-sharp" /></template>
<style>
.ro9ouknln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.37 3.83l1.01-.66l.62-.42l.6.45l.8.6l.6.45l.6-.45l.8-.6l.6-.45l.6.45l.8.6l.6.45l.6-.45l.8-.6l.6-.45l.62.42l1.01.66l.62.42l.02.75l.46 15.5l.02.75H5.25l.02-.75L5.73 5l.02-.75zm-.72 3.92h12.7m-6.35 0v3");
}

</style>
