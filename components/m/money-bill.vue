<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jldw8tb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jldw8tb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-bill" /></template>
