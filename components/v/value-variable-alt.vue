<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo8vbxb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fo8vbxb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:value-variable-alt" /></template>
