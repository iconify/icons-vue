<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv2_vmbmc.css';
import '../../css/d/djk4s6bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zv2_vmbmc"/><path class="djk4s6bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:repo-source-code" /></template>
