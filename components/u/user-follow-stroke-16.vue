<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo3soyo3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eo3soyo3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-follow-stroke-16" /></template>
