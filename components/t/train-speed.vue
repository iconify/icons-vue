<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eef4yzd1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eef4yzd1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:train-speed" /></template>
