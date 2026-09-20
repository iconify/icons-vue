<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1-c_j9ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y1-c_j9ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:rectangle-split-thirds" /></template>
