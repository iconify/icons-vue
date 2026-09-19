<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk8zlsbsk.css';
import '../../css/s/svdkxk0qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jk8zlsbsk"/><path class="svdkxk0qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:touch-1" /></template>
