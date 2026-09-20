<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":332};
const content = `<defs><linearGradient id="SVGL9oVpcfY" x1="55.117%" x2="63.68%" y1="58.68%" y2="39.597%"><stop offset="0%" class="h-htnbcov"/><stop offset="53%" class="h79w7ebun"/><stop offset="100%" class="y15y19baw"/></linearGradient></defs><path fill="url(#SVGL9oVpcfY)" class="e3930cyph"/><path class="a07kqu_br"/><path class="vf7123vwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:sublimetext-icon" /></template>
<style>
.a07kqu_br {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M0 164.291c0 3.887 2.865 7.95 6.397 9.071l242.53 76.902c3.531 1.12 6.397-1.127 6.397-5.007V166.66c0-3.88-2.866-7.944-6.397-9.064L6.397 80.694C2.865 79.574 0 81.814 0 85.7z");
}

.e3930cyph {
  d: path("M255.288 166.795c0-3.887-2.872-6.128-6.397-5.015L6.397 238.675C2.865 239.796 0 243.86 0 247.74v78.59c0 3.887 2.865 6.135 6.397 5.015l242.494-76.888c3.525-1.12 6.397-5.185 6.397-9.071z");
}

.h-htnbcov {
  stop-color: var(--svg-color--ff9700, #ff9700);
}

.h79w7ebun {
  stop-color: var(--svg-color--f48e00, #f48e00);
}

.vf7123vwl {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M255.288 5.302c0-3.886-2.872-6.135-6.397-5.014L6.397 77.176C2.865 78.296 0 82.36 0 86.247v78.59c0 3.887 2.865 6.128 6.397 5.014l242.494-76.895c3.525-1.12 6.397-5.184 6.397-9.064z");
}

.y15y19baw {
  stop-color: var(--svg-color--d06f00, #d06f00);
}

</style>
