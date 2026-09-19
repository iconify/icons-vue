<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh3i9mbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qh3i9mbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mask-ventilator" /></template>
