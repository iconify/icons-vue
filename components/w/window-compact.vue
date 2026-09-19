<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3jerqblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="o3jerqblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:window-compact" /></template>
