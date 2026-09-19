<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrifaiata.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nrifaiata"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:y-axis" /></template>
