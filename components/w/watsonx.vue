<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yelbti8fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yelbti8fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:watsonx" /></template>
