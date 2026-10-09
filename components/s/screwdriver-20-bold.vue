<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag31uv8-s.css';
import '../../css/n/nlpbp5but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ag31uv8-s"/><path class="nlpbp5but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screwdriver-20-bold" /></template>
