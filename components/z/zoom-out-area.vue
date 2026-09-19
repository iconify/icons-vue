<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivkxfbb3l.css';
import '../../css/q/qmvfbubxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ivkxfbb3l"/><path class="qmvfbubxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-out-area" /></template>
