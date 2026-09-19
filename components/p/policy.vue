<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/occxhccgf.css';
import '../../css/m/mxusxgb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="occxhccgf"/><path class="mxusxgb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:policy" /></template>
