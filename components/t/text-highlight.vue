<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-jxcu6vs.css';
import '../../css/x/xq-7sgbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i-jxcu6vs"/><path class="xq-7sgbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-highlight" /></template>
