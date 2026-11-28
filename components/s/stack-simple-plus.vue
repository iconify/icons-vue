<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqa0afbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oqa0afbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:stack-simple-plus" /></template>
