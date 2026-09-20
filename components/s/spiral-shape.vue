<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/widswmrqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="widswmrqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spiral-shape" /></template>
