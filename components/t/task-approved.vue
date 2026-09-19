<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb7z8wwtr.css';
import '../../css/r/rututhb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sb7z8wwtr"/><path class="rututhb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-approved" /></template>
