<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txri1yb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="txri1yb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:product-categories" /></template>
