<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-3oclb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":502,"height":512};
const content = `<path class="e-3oclb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:totvs" /></template>
