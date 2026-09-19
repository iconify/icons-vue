<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8ll97trp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8ll97trp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:use-case-include" /></template>
