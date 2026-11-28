<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eri-gxboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eri-gxboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ungroup-fill" /></template>
