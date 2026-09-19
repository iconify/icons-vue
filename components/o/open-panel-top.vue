<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whnn-4bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="whnn-4bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:open-panel-top" /></template>
