<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255};
const content = `<defs><linearGradient id="SVGg39WleeP" x1="12.959%" x2="79.639%" y1="12.039%" y2="78.201%"><stop offset="0%" class="aw-t_bg-j"/><stop offset="100%" class="z8bgr0bko"/></linearGradient><linearGradient id="SVGlXoRkc4T" x1="19.128%" x2="90.742%" y1="20.579%" y2="88.429%"><stop offset="0%" class="h2odc0bvt"/><stop offset="100%" class="jxpbwgawm"/></linearGradient></defs><path fill="url(#SVGg39WleeP)" class="t-icsv38j"/><path fill="url(#SVGlXoRkc4T)" class="lui1pabdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:python" /></template>
<style>
.aw-t_bg-j {
  stop-color: var(--svg-color--387eb8, #387eb8);
}

.h2odc0bvt {
  stop-color: var(--svg-color--ffe052, #ffe052);
}

.jxpbwgawm {
  stop-color: var(--svg-color--ffc331, #ffc331);
}

.lui1pabdf {
  d: path("M128.757 254.126c64.832 0 60.784-28.115 60.784-28.115l-.072-29.127H127.6v-8.745h86.441s41.486 4.705 41.486-60.712c0-65.416-36.21-63.096-36.21-63.096h-21.61v30.355s1.165 36.21-35.632 36.21h-61.362s-34.475-.557-34.475 33.32v56.013s-5.235 33.897 62.518 33.897m34.114-19.586a11.12 11.12 0 0 1-11.13-11.13a11.12 11.12 0 0 1 11.13-11.131a11.12 11.12 0 0 1 11.13 11.13a11.12 11.12 0 0 1-11.13 11.13");
}

.t-icsv38j {
  d: path("M126.916.072c-64.832 0-60.784 28.115-60.784 28.115l.072 29.128h61.868v8.745H41.631S.145 61.355.145 126.77c0 65.417 36.21 63.097 36.21 63.097h21.61v-30.356s-1.165-36.21 35.632-36.21h61.362s34.475.557 34.475-33.319V33.97S194.67.072 126.916.072M92.802 19.66a11.12 11.12 0 0 1 11.13 11.13a11.12 11.12 0 0 1-11.13 11.13a11.12 11.12 0 0 1-11.13-11.13a11.12 11.12 0 0 1 11.13-11.13");
}

.z8bgr0bko {
  stop-color: var(--svg-color--366994, #366994);
}

</style>
