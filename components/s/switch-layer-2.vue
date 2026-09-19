<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy91uv1gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oy91uv1gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:switch-layer-2" /></template>
