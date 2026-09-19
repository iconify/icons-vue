<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td-rczbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="td-rczbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rain-scattered" /></template>
