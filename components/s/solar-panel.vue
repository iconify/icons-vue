<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxe0xlbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mxe0xlbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:solar-panel" /></template>
