<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmpb39b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qmpb39b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:metadata-definition" /></template>
