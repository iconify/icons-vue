<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7fxexb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p7fxexb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mcp-compact" /></template>
