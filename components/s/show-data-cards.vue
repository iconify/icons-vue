<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwzq6cb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dwzq6cb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:show-data-cards" /></template>
