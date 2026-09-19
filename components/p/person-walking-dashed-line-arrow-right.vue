<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etdkoebcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="etdkoebcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-walking-dashed-line-arrow-right" /></template>
