<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ion3i0afj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ion3i0afj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:page-template" /></template>
