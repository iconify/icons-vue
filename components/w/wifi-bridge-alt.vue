<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1o5-ybgl.css';
import '../../css/c/cr1pj8fpu.css';
import '../../css/m/mh4pb4b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i1o5-ybgl"/><path class="cr1pj8fpu"/><path class="mh4pb4b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wifi-bridge-alt" /></template>
