<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_qiu8wtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_qiu8wtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subtract" /></template>
