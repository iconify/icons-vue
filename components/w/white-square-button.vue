<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gb7dsabnw"/><path class="gh40vebvi"/><path class="r5l4ibcfw"/><path class="tyb3j6i0z"/><path class="uboa56e7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:white-square-button" /></template>
<style>
.gb7dsabnw {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.gh40vebvi {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.r5l4ibcfw {
  fill: var(--svg-color--575757, #575757);
  d: path("M28.1 24.7h73c1.6 0 2.9 1.3 2.9 2.9v73c0 1.6-1.3 2.9-2.9 2.9h-73c-1.6 0-2.9-1.3-2.9-2.9V27.7a2.863 2.863 0 0 1 2.72-3z");
}

.tyb3j6i0z {
  fill: var(--svg-color--424242, #424242);
  d: path("M28.1 24.7h67.4c1.6 0 2.9 1.3 2.9 2.9V95c0 1.6-1.3 2.9-2.9 2.9H28.1c-1.6 0-2.9-1.3-2.9-2.9V27.7a2.863 2.863 0 0 1 2.72-3z");
}

.uboa56e7n {
  fill: var(--svg-color--787878, #787878);
  d: path("M49 33.5c0-1.5-1-1.9-6.9-1.7c-4.9.2-7.3.8-8.8 2.6s-1.9 5.4-1.9 9.8c0 3.1 0 5.9 1.6 5.9c2.2 0 2.2-5 4-7.9c3.3-5.5 12-6.7 12-8.7");
}

</style>
