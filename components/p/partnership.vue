<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey8xpjbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ey8xpjbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partnership" /></template>
