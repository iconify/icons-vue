<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir5lyl61v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ir5lyl61v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:o-square" /></template>
