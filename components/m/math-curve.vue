<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuxfbccad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kuxfbccad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:math-curve" /></template>
