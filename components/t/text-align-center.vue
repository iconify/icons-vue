<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3ug6bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ye3ug6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-align-center" /></template>
