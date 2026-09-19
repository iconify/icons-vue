<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo9o1ccjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eo9o1ccjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reset-alt" /></template>
