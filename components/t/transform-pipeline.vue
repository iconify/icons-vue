<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s78iaqrgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s78iaqrgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:transform-pipeline" /></template>
