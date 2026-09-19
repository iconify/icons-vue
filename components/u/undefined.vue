<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t19jz2bby.css';
import '../../css/y/yti26qboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t19jz2bby"/><path class="yti26qboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:undefined" /></template>
