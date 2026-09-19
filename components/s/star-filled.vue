<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3ta31sjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y3ta31sjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:star-filled" /></template>
