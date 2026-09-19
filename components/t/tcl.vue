<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny4xytvip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":242,"height":512};
const content = `<path clip-rule="evenodd" class="ny4xytvip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tcl" /></template>
