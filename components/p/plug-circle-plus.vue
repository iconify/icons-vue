<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4v16fbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g4v16fbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plug-circle-plus" /></template>
