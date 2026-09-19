<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc6qyrb-v.css';
import '../../css/q/qrq26sblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cc6qyrb-v"/><path class="qrq26sblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unsaved" /></template>
