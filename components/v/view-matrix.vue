<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcor-1yvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcor-1yvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-matrix" /></template>
