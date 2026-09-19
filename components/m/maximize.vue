<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjn-p1eni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjn-p1eni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:maximize" /></template>
