<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrt-k2bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zrt-k2bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbs-up-double" /></template>
