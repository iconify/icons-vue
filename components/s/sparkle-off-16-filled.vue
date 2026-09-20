<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qkwt3gmjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-off-16-filled" /></template>
<style>
.qkwt3gmjt {
  fill: currentColor;
  d: path("M14.147 1.146a.5.5 0 1 1 .707.708l-13 13a.5.5 0 0 1-.708-.707zm-3.045 6.858a.8.8 0 0 1 .637.53l.252.773a1.08 1.08 0 0 0 .68.678l.765.25a.8.8 0 0 1 .022 1.52l-.771.252a1.05 1.05 0 0 0-.42.259a1.1 1.1 0 0 0-.26.42l-.248.763a.8.8 0 0 1-.301.4a.8.8 0 0 1-.459.15a.81.81 0 0 1-.757-.536l-.253-.773a1.06 1.06 0 0 0-.68-.684l-.763-.247a.81.81 0 0 1-.54-.64a.8.8 0 0 1 .528-.88l.777-.254a1.08 1.08 0 0 0 .664-.68l.247-.761a.8.8 0 0 1 .88-.54M5.98 2.003c.19 0 .377.058.534.166c.155.11.272.265.336.444l.35 1.084a1.7 1.7 0 0 0 1.08 1.078l.621.2l-3.928 3.93l-.198-.604a1.7 1.7 0 0 0-.412-.668a1.7 1.7 0 0 0-.669-.415L2.63 6.87a.924.924 0 0 1-.014-1.745l1.084-.35a1.71 1.71 0 0 0 1.049-1.06l.356-1.09a.92.92 0 0 1 .875-.623");
}

</style>
