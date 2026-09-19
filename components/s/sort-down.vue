<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euns1ebio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="euns1ebio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:sort-down" /></template>
