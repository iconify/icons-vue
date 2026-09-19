<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl5lsw3qs.css';
import '../../css/z/zzcp-vb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cl5lsw3qs"/><path class="zzcp-vb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ticket" /></template>
