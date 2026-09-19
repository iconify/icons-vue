<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doi5vbbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="doi5vbbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:view-in-a-r" /></template>
