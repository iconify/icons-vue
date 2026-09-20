<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yor0a7bzn.css';
import '../../css/h/hir2mbb0k.css';
import '../../css/h/hj176wbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yor0a7bzn"/><path class="hir2mbb0k"/><path class="hj176wbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:webhook-16" /></template>
