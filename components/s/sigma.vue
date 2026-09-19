<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awms53bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="awms53bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sigma" /></template>
