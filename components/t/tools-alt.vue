<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj94jcb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xj94jcb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tools-alt" /></template>
