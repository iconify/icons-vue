<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o205f_btu"/><path class="vlfltdbow"/><path class="i5sat9b9q"/><path class="a0bx8w9jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:next-track-button" /></template>
<style>
.a0bx8w9jm {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 4.125-3 10.925c0 4.8.553 9.3 2.233 9.3c1.157 0 1.682-.498 2.506-1.56c1.653-2.131 3.6-5.456 5.487-8.423C27.886 16.353 39.7 15.9 39.7 12.9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i5sat9b9q {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M107.1 36H96.9a1.9 1.9 0 0 0-1.9 1.9v23.5l-35.9-25c-.98-.58-2.24-.26-2.82.72c-.23.39-.33.84-.28 1.28v22.3L21 36.3c-1.4-.9-3 .2-3 2v51.4c0 1.8 1.7 2.9 3 2l35-24.4v22.3c-.13 1.13.69 2.15 1.82 2.28c.45.05.9-.05 1.28-.28l35.9-25v23.5c0 1.05.85 1.9 1.9 1.9h10.3a1.9 1.9 0 0 0 1.9-1.9V37.9c-.05-1.07-.93-1.9-2-1.9");
}

.o205f_btu {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.vlfltdbow {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
