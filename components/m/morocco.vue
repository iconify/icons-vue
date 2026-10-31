<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq6tdnpts.css';
import '../../css/t/t3di-p3xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="sq6tdnpts"/><path class="t3di-p3xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:morocco" /></template>
