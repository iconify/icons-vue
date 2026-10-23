<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga7_-ybll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ga7_-ybll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:parallelogram-solid" /></template>
