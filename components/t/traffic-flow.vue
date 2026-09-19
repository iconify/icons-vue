<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep-7nhd8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ep-7nhd8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:traffic-flow" /></template>
