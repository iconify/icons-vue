<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po_ex1brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="po_ex1brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:succession-flow-connection" /></template>
