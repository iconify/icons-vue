<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7xrhg4uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="t7xrhg4uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:rotate-clockwise" /></template>
