<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8stgrckh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l8stgrckh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:row-collapse" /></template>
