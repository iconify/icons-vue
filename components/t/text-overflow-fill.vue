<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l639ivboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l639ivboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-overflow-fill" /></template>
