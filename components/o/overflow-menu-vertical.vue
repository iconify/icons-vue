<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssbjp9b9f.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/n/nge6tfbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ssbjp9b9f"/><circle class="e39ud6bwf"/><circle class="nge6tfbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:overflow-menu-vertical" /></template>
