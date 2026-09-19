<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8er1hxdx.css';
import '../../css/a/a3f5iab8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y8er1hxdx"/><path class="a3f5iab8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pricing-tailored" /></template>
