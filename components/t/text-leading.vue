<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5m82iwwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t5m82iwwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-leading" /></template>
