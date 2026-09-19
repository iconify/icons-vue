<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t76c8zbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="t76c8zbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:map" /></template>
