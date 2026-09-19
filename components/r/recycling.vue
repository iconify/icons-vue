<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znffry7mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="znffry7mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:recycling" /></template>
