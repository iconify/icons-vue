<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0_g-seyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p0_g-seyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:z-axis" /></template>
