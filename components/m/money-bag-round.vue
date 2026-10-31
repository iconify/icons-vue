<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z39q21b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z39q21b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:money-bag-round" /></template>
