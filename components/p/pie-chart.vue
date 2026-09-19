<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlepf_eml.css';
import '../../css/q/qbsvsyi4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nlepf_eml"/><path class="qbsvsyi4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:pie-chart" /></template>
