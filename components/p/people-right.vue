<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce08mxb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ce08mxb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:people-right" /></template>
