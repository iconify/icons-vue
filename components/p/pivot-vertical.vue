<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgfy-nl4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgfy-nl4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pivot-vertical" /></template>
