<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cik39oe1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cik39oe1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wind-power" /></template>
