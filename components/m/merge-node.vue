<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nua10xqcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nua10xqcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:merge-node" /></template>
