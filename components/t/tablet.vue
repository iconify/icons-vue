<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu6eqibhi.css';
import '../../css/n/n6mum1zrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iu6eqibhi"/><path class="n6mum1zrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tablet" /></template>
