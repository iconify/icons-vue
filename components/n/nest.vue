<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3qgmzeta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="d3qgmzeta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nest" /></template>
