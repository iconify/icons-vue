<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkaoz6bjf.css';
import '../../css/o/oztuellfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zkaoz6bjf"/><path class="oztuellfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:train-ticket" /></template>
