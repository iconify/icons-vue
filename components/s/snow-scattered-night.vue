<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo0-vdo8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qo0-vdo8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:snow-scattered-night" /></template>
