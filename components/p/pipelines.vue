<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okikuvbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="okikuvbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pipelines" /></template>
