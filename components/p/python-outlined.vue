<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wk51pcbgt.css';
import '../../css/v/vaj17wbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g class="n1lsf0bnc"><path class="wk51pcbgt"/><path class="vaj17wbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:python-outlined" /></template>
