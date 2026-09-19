<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udtx5jbky.css';
import '../../css/k/kggl2nbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="udtx5jbky"/><path class="kggl2nbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-incoming-filled" /></template>
