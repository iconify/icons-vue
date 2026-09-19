<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wummjl_3r.css';
import '../../css/q/qpjvcje9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wummjl_3r"/><path class="qpjvcje9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:package-text-analysis" /></template>
