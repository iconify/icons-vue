<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o29mefbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o29mefbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:retry-failed" /></template>
