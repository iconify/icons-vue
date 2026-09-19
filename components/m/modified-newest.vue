<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x55r3nbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x55r3nbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:modified-newest" /></template>
