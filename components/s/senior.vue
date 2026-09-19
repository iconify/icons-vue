<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv11-qf5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1792};
const content = `<path class="uv11-qf5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:senior" /></template>
