<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9l0rm1ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x9l0rm1ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partition-specific" /></template>
