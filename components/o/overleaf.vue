<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh80ltb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zh80ltb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:overleaf" /></template>
