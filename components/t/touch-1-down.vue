<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2l7ej-yh.css';
import '../../css/x/xtkb6fvqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f2l7ej-yh"/><path class="xtkb6fvqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:touch-1-down" /></template>
