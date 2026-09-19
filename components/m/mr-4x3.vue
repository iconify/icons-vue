<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei-fevb0d.css';
import '../../css/g/gefsnvbmp.css';
import '../../css/q/qx32elbez.css';
import '../../css/d/dlkwv-bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="ei-fevb0d"/><path class="gefsnvbmp"/><path class="mr-st1 qx32elbez"/><path class="dlkwv-bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mr-4x3" /></template>
