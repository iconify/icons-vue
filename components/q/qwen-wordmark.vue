<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx15z85sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cx15z85sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:qwen-wordmark" /></template>
