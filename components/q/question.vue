<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di0umsr9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="di0umsr9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:question" /></template>
