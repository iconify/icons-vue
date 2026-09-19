<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovamrv60q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ovamrv60q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:smoke" /></template>
