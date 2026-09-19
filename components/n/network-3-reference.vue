<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p45gor59d.css';
import '../../css/d/doyyo9bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p45gor59d"/><path class="doyyo9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-3-reference" /></template>
