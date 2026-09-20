<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh5q-1lmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qh5q-1lmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:upload" /></template>
