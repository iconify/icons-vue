<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpl92qbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dpl92qbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:portfolio-groups" /></template>
