<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":261};
const content = `<path class="ergkibm0b"/><path class="cgboiacgs"/><path class="qp5po1pye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:proofy" /></template>
<style>
.cgboiacgs {
  fill: var(--svg-color--fff, #fff);
  d: path("m200.817 72.055l-72.048 42.913l-72.047-42.913zm0 72.048L128.77 187.03l-72.047-42.928v-55.19l72.04 42.929l72.048-42.93v55.192zm6.135-87.374H50.58c-3.064 0-6.128 3.064-6.128 7.659v79.73c0 3.07 0 9.198 6.128 12.247c6.134 4.603 78.182 47.53 78.182 47.53s72.048-42.913 78.19-47.53c6.12-4.588 6.12-9.184 6.12-12.247v-79.73c0-4.595-1.525-7.66-6.12-7.66");
}

.ergkibm0b {
  fill: var(--svg-color--13c779, #13c779);
  d: path("M141.032 0H12.255C6.128 0 0 6.127 0 12.269v162.5c0 7.644 4.603 16.865 10.723 19.928l107.309 62.857c6.135 4.588 15.333 4.588 19.936 0l107.302-62.857c6.127-4.602 10.73-12.27 10.73-19.928v-162.5C256 4.603 249.866.007 243.738.007H141.032z");
}

.qp5po1pye {
  fill: var(--svg-color--231f1f, #231f1f);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M128.762 0H12.254C6.127 0 0 6.127 0 12.269v162.5c0 7.644 4.603 16.865 10.723 19.928l107.31 62.857c3.062 1.525 6.134 3.064 10.722 3.064z");
}

</style>
