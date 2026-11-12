<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="vebkkh5gh"/><path class="fo8dlab0r"/><path class="d6c-fzbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-4-bold-duotone" /></template>
<style>
.d6c-fzbcb {
  fill: currentColor;
  d: path("M20.9854 16.25C20.9746 16.8031 20.9559 17.3007 20.9199 17.75L3.08105 17.75C3.04507 17.3006 3.02635 16.8032 3.01562 16.25L20.9854 16.25Z");
}

.fo8dlab0r {
  fill: currentColor;
  d: path("M3.01562 7.75C3.02635 7.19683 3.04507 6.69936 3.08105 6.25L20.9199 6.25C20.9559 6.69935 20.9746 7.19686 20.9854 7.75L3.01562 7.75Z");
}

.nayqy1c_r {
  fill: currentColor;
  d: path("M13 2C16.7712 2 18.6569 2 19.8284 3.17157C21 4.34315 21 6.22876 21 10L21 14C21 17.7712 21 19.6569 19.8284 20.8284C18.6569 22 16.7712 22 13 22L11 22C7.22876 22 5.34315 22 4.17157 20.8284C3 19.6569 3 17.7712 3 14L3 10C3 6.22876 3 4.34315 4.17157 3.17157C5.34315 2 7.22876 2 11 2L13 2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vebkkh5gh {
  fill: currentColor;
  d: path("M3 12.75L3 11.25L21 11.25L21 12.75L3 12.75Z");
}

</style>
