<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxrugac4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yxrugac4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:semi-select" /></template>
