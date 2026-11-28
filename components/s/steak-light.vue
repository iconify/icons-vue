<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb7y0rb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sb7y0rb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:steak-light" /></template>
