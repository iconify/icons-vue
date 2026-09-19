<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udtx5jbky.css';
import '../../css/t/t134q6seg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="udtx5jbky"/><path class="t134q6seg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-block-filled" /></template>
