<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydcngk_0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ydcngk_0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:underline-16-solid" /></template>
