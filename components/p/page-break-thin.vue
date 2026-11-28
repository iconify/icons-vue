<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx9chsbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dx9chsbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:page-break-thin" /></template>
