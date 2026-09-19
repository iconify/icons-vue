<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5zn4-brr.css';
import '../../css/z/zxlwz1bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b5zn4-brr"/><path class="zxlwz1bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-mining" /></template>
