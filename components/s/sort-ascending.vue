<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cymrcsbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cymrcsbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sort-ascending" /></template>
