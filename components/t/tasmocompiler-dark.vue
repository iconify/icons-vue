<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy4-wlswh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qy4-wlswh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmocompiler-dark" /></template>
