<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fego9bj_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fego9bj_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-search" /></template>
