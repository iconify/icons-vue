<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtli1d3xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dtli1d3xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:medal-ribbon-with-circle" /></template>
