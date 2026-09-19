<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j35eaocdf.css';
import '../../css/d/d3ppxtb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j35eaocdf"/><path class="d3ppxtb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-up" /></template>
