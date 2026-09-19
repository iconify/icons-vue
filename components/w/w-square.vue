<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3-k1fbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="p3-k1fbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:w-square" /></template>
