<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d80gbh72b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d80gbh72b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:picnic-area" /></template>
