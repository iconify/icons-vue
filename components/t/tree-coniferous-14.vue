<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-saaebsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h-saaebsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:tree-coniferous-14" /></template>
